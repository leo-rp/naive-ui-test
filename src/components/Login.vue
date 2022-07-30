<template>


  <n-gradient-text type="info">
    the Vue3 
  </n-gradient-text>
  <n-gradient-text type="danger">
     + 
  </n-gradient-text>
  
  <n-gradient-text :size="24" type="warning">
     Naive-ui 
  </n-gradient-text>
  
  <n-gradient-text :size="24" type="success">
     test WSS!
  </n-gradient-text>

  <n-space>
    <span style="font-variant-numeric: tabular-nums">
      <n-countdown :duration="5000" :active="active" />
    </span>
    <n-switch v-model:value="active" />
  </n-space>
</template>

<script lang="ts">
import { defineComponent, ref } from 'vue'


export default defineComponent({
	
  setup () {
    return {
      active: ref(false)
    }
  }
})
</script>

<style scoped>
.n-gradient-text {
  font-size: 36px;
}
</style>
