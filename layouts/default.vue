<template>
  <el-container class="container">
    <layout-header />
    <el-main>
      <nuxt/>
    </el-main>
    <el-footer>
      &nbsp;
    </el-footer>
  </el-container>
</template>

<script>
import LayoutHeader from './header'
export default {
  components: { LayoutHeader }
}
</script>

<style>
html {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  color: #35495e;
  font-size: 16px;
  word-spacing: 1px;
  height: 100%;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.width-wrap {
  width: 1180px;
  margin: 0 auto;
}

.el-main {
  min-height: 320px;
}

a {
  color: #4e4e4e;
  text-decoration: inherit;
}

a:hover {
  color: #409EFF;
}
</style>
