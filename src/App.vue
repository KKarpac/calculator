<template>
  <div id="app">
    <Calculator msg="Calculator"/>
  </div>
</template>

<script>
import Calculator from './components/Calculator.vue'

export default {
}
</script>

<style>
  .calculator {
    grid-template-columns: (4, 1fr);

  }
</style>
