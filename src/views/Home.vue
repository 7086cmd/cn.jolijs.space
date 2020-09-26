<template>
  <div class="home">
    <h1>Joli.js</h1>
    <h2>新一代Electron工具</h2>
    <p>特点：</p>
    <ul>
      <li>内置各种工具</li>
      <li>模板生成</li>
      <li>...</li>
    </ul>
    <a-card :hoverable="true">
      <h3>Latest</h3>
      0.0.1
    </a-card>
    <a-card :hoverable="true">
      <h3>Beta</h3>
      0.0.1
    </a-card>
    <a-card :hoverable="true">
      <h3>Nightly</h3>
      0.0.1
    </a-card>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>

<style lang="less">
div {
  text-align: left;
  padding-left: 20px
}
</style>