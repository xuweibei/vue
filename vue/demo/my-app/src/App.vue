<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    {{meg}} -->
    {{message}}
    <span v-html="lslls">456</span>
    <input v-model="meg" />
    <p>{{lalala}}</p>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  datas:{
    message:132
  },
  components: {
    // HelloWorld
  },
  computed:{
    lalala:function(){
      return 456
    }
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
