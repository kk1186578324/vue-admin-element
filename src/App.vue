<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>

    {{obj.mag}}
    {{obj.yc}}
    {{mag}}
    <button @click="btnClick">dsasda</button>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
    data(){
      return{
          obj:{
              mag:'12fsdf'
          },
          mag:'qwrewrewerwe'

      }

    },
  components: {
    HelloWorld
  },

  methods:{

      btnClick(){
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
