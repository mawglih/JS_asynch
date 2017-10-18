<template>
  <div id="app">
    <h1 class="text-center">{{msg}}</h1>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Generate your starbase team'
    }
  }
}
</script>

<style>
  body {
    background-color: #263238;
    color: bisque;
  }
  #app {
     font-family: 'Avenir', Arial, Helvetica, sans-serif;
     text-align:center;
     margin-top:60px;
  }
</style>
