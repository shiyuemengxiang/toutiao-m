<template>
  <div id="app">
    <center><h1>头条</h1></center>
    <router-view/>
  </div>
</template>
<script>
export default {
  name: 'App',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  methods: {
    changeMsg () {
      this.msg = 'Welcome to Your Vue.js App (changed)'
    }
  }
}

</script>
<style lang="less">

</style>
