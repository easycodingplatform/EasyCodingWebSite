<template>
  <div id="app">
    <el-container>
      <el-header class="bottom-line">
        <page-header/>
      </el-header>
      <router-view/>
    </el-container>
  </div>
</template>

<script>
import PageHeader from './components/PageHeader'
export default {
  name: 'App',
  components: {
    'page-header': PageHeader
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}
.bottom-line
{
    border-bottom-style: solid;
    border-bottom-color: rgba(187,187,187,0.4);
    border-bottom-width: 1px;
}
</style>
