<template>
<div>
  <el-container>
    <app-aside></app-aside>
    <el-container>
      <el-header>
        <app-header> 积云编程132456789</app-header>
      </el-header>
      <el-main>
        <bread-crumbs></bread-crumbs>
        <app-main></app-main>
      </el-main>
    </el-container>
  </el-container>
  </div>
</template>

<script>
import AppAside from '@/layout/AppAside'
import AppMain from '@/layout/AppMain'

export default {
  data() {
    return {}
  },
  mounted() {},
  methods: {},
  components: {
    AppAside,
    AppMain
  }
}
</script>

<style lang="scss">
.el-header {
  background-color: #655cde;
  color: #000;
  font-size: 25px;
}

.el-aside {
  background-color: #222d32;
  color: #fff;
}

.el-main {
  background-color: #e9eef3;
  color: #333;
}

.el-container {
  margin-bottom: 40px;
  height: 100%;
}
</style>
