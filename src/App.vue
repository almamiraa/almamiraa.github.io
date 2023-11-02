<template>
  <div id="APP">
    <CalculatorApp> </CalculatorApp>
  </div>
</template>

<script>
import CalculatorApp from './components/CalculatorApp.vue'

export default {
  name: 'App',
  components: {
    CalculatorApp
}
}
</script>

<style>
  body {
    background: #5888bb !important;
  }
</style>