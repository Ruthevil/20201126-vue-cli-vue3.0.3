<template>
  <HelloWorld msg="小伙子，快来学习vue3.0.3了！"></HelloWorld>
</template>

<script>
  import HelloWorld from "@/components/HelloWorld.vue"

  export default {
    name: "App",
    components: {
      HelloWorld
    }
  }
</script>

<style lang="stylus">
  #app
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
</style>
