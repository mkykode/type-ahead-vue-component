<template>
    <div id="app">
        <AutoComplete></AutoComplete>
    </div>
</template>

<script>
  import AutoComplete from './components/Ac.vue'

  export default {
    name: 'app',
    components: {
      AutoComplete,
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
