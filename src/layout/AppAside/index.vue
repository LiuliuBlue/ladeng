<template>
  <div class="asd">
    <el-menu
      default-active="2"
      class="el-menu-vertical-demo"
      text-color="#000"
      active-text-color="#ffd04b"
    >
      <el-submenu index="1">
        <template slot="title">
          <i class="el-icon-location"></i>
          <span>后台面板</span>
        </template>
        <el-menu-item index="1-3">主控台</el-menu-item>
      </el-submenu>
      <el-submenu index="1">
        <template slot="title">
          <i class="el-icon-location"></i>
          <span>商品管理</span>
        </template>
        <el-menu-item index="1-3">商品管理</el-menu-item>
        <el-menu-item index="1-4-1">分类管理</el-menu-item>
        <el-menu-item index="1-3">规格管理</el-menu-item>
        <el-menu-item index="1-4-1">优惠券管理</el-menu-item>
      </el-submenu>
      <el-submenu index="1">
        <template slot="title">
          <i class="el-icon-location"></i>
          <span>用户管理</span>
        </template>
        <el-menu-item index="1-3">用户管理</el-menu-item>
        <el-menu-item index="1-4-1">会员等级</el-menu-item>
      </el-submenu>
      <el-submenu index="1">
        <template slot="title">
          <i class="el-icon-location"></i>
          <span>订单管理</span>
        </template>
        <el-menu-item index="1-3">订单管理</el-menu-item>
        <el-menu-item index="1-4-1">评论管理</el-menu-item>
      </el-submenu>
      <el-submenu index="1">
        <template slot="title">
          <i class="el-icon-location"></i>
          <span>管理员管理</span>
        </template>
        <el-menu-item index="1-3">管理员管理</el-menu-item>
        <el-menu-item index="1-4-1">权限管理</el-menu-item>
        <el-menu-item index="1-3">角色管理</el-menu-item>
      </el-submenu>
      <el-submenu index="1">
        <template slot="title">
          <i class="el-icon-location"></i>
          <span>系统设置</span>
        </template>
        <el-menu-item index="1-3">基础设置</el-menu-item>
        <el-menu-item index="1-4-1">交易设置</el-menu-item>
        <el-menu-item index="1-3">物流设置</el-menu-item>
      </el-submenu>
      <el-submenu index="1">
        <template slot="title">
          <i class="el-icon-location"></i>
          <span>分校模块</span>
        </template>
        <el-menu-item index="1-3">分销员管理</el-menu-item>
        <el-menu-item index="1-4-1">分销设置</el-menu-item>
      </el-submenu>
      <el-submenu index="1">
        <template slot="title">
          <i class="el-icon-location"></i>
          <span>其他模块</span>
        </template>
        <el-menu-item index="1-3">土库管理</el-menu-item>
        <el-menu-item index="1-4-1">公告管理</el-menu-item>
      </el-submenu>
    </el-menu>
  </div>
</template>

<script>
export default {
  data() {
    return {}
  },
  mounted() {},
  methods: {},
  components: {}
}
</script>

<style lang="scss">
.asd {
  width: 230px;
}
</style>
