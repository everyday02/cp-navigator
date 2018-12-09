<template lang="html">
  <el-container>
    <el-header>Header</el-header>
    <el-main>Main</el-main>
    <el-footer>Footer</el-footer>
  </el-container>
</template>

<script>
export default {
  head: {
    titleTemplate: '首页',
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },
      { hid: 'description', name: 'description', content: 'Meta description' }
    ]
  },
  data () {
    return {}
  },
  computed: {},
  ready () {},
  attached () {},
  methods: {}
}
</script>

<style lang="css">
</style>
