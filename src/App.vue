<template>
  <div id="app">
    <vant-button type="primary">测试 vant 组件库</vant-button>
  </div>
</template>

<script>
import { Button } from 'vant'

export default {
  name: 'App',
  components: {
    [Button.name] : Button
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
