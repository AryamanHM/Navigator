<template>
  <div id="app">
    <PlannerItem/>
  </div>
</template>

<script>
import PlannerItem from './views/PlannerItem.vue'

export default {
  name: 'app',
  components: {
    PlannerItem
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
  body {
    margin: 0;
  }
</style>
