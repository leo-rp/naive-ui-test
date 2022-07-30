<script>
  import { defineComponent } from 'vue'
  
  // theme
  import { createTheme, inputDark, datePickerDark } from 'naive-ui'
  // locale & dateLocale
  //import { zhCN, dateZhCN } from 'naive-ui'

  export default defineComponent({
    
    setup() {
      return {
        darkTheme: createTheme([inputDark, datePickerDark]),
        //zhCN,
        //dateZhCN
      }
    }
  })
</script>

<template>
  <n-config-provider >
    <n-space vertical>
      <n-input />
      <n-date-picker />
    </n-space>
  </n-config-provider>
</template>

<style>
  
</style>