<template>
  <div id="app">
    <TitleTest msg="La mia prima app con Vue CLI!"/>
  </div>
</template>

<script>
import TitleTest from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    TitleTest,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
