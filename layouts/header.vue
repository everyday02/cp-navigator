<template lang="html">
  <el-header
    class="layout-header width-wrap"
    style="padding: 0px; height: 180px;" >
    <h1 class="title">
      如何成为产品经理
    </h1>
    <el-menu
      :default-active="activeIndex"
      class="layout-header-menu"
      mode="horizontal"
      @select="handleSelect">
      <el-menu-item
        index="1">
        <i class="el-icon-menu" />
        <span>UI界面设计</span>
      </el-menu-item>
    </el-menu>
  </el-header>
</template>

<script>
export default {
  data () {
    return {
      activeIndex: '1'
    }
  },
  computed: {},
  ready () {},
  attached () {},
  methods: {
    handleSelect(key, keyPath) {
      // console.info(key, keyPath);
    }
  }
}
</script>

<style lang="css">
.layout-header {
  color: white;
  background: #255880;
  text-align: center;
}
.layout-header-menu {
  /*top: 151px;*/
}
.title {
  height: 120px;
  line-height: 120px;
  font-weight: 300;
  font-size: 36px;
  letter-spacing: 1px;
}
</style>
