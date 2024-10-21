<script setup>
import { ref } from 'vue'

const testHtml = ref("<span style=\"color: red\">This should be red.</span>")

</script>

<template>
  <p v-html="testHtml"></p>
</template>