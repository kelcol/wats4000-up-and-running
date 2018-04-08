<template>
  <div id="app">
    <custom></custom>
    <editor></editor>
    
  </div>
</template>

<script>
import Editor from './components/Editor'
import Custom from './components/Custom'

export default {
  name: 'app',
  components: {
    Editor, Custom
  },

}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
