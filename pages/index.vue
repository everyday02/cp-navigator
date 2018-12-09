<template>
  <div class="ui-container width-wrap">
    <el-row>
      <el-col
        v-for="data in datas"
        :key="data.link"
        :span="6"
        class="box-card">
        <el-card
          shadow="hover">
          <a
            :href="data.link"
            target="_blank">
            {{ data.name }}
          </a>
        </el-card>
      </el-col>
    </el-row>
  </div>
</template>
<script>

export default {
  head: {
    titleTemplate: '产品经理,产品经理导航',
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },
      { hid: 'description', name: 'description', content: '产品经理,产品经理导航' }
    ]
  },
  data () {
    return {
      datas: [
        { name: '腾讯CDC', link: 'https://cdc.tencent.com/' },
        { name: '百度MUX', link: 'http://uxc.baidu.com/' },
        { name: 'UI 中国', link: 'https://www.ui.cn/'},
        { name: '站酷网', link: 'https://www.zcool.com.cn/'}
      ]
    }
  }
}
</script>

<style>
.box-card {
  padding: 10px;
}
.box-card:hover {
  color: #409EFF;
}
</style>
