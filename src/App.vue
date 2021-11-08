<template>
  <Toggle msg="Shabnam"/>
</template>

<script>
import Toggle from './components/toggle.vue'

export default {
  name: 'App',
  components: {
    Toggle
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
