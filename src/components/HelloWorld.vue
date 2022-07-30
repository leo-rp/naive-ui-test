<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  
  <n-gradient-text
    gradient="linear-gradient(90deg, red 0%, green 50%, blue 100%)"
  >
    {{msg}}
  </n-gradient-text>
</template>

<style scoped>
.n-gradient-text {
  font-size: 24px;
}
</style>