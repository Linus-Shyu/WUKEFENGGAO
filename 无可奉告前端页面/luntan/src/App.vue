<template>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <JuanZeng></JuanZeng>
  <JieShao></JieShao>
  <LiZi></LiZi>
</template>

<script>
import JuanZeng from './components/JuanZeng.vue'
import JieShao from './components/JieShao.vue'
export default {
  name: 'App',
  components: {
    JuanZeng,
    JieShao,
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