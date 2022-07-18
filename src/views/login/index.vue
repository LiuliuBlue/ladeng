<template>
 <div class="home">
    <div class="zuo">
      <span>欢迎光临</span>
    </div>
    <div class="you">
      <div class="dl">
        <span class="hl">欢迎回来</span>
        <div class="ma">输入账号密码登录</div>
        <div class="in">
          <input type="text" placeholder="请输入账号" /><br />
          <input type="text" placeholder="请输入密码" />
        </div>
        <div class="bu" @click="den">登录</div>
      </div>
    </div>
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
.home {
  width: 100%;
  height: 100vh;
  display: flex;
  .zuo {
    width: 70%;
    height: 100vh;
    background-color: #6466e9;
    text-align: center;
    font-size: 50px;
    color: #fff;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .you {
    width: 30%;
    height: 100vh;
    font-size: 50px;
    text-align: center;
    justify-content: center;
    align-items: center;
    position: relative;
    .dl {
      width: 500px;
      height: 500px;
      position: absolute;
      top: 30vh;
      .hl {
        font-size: 50px;
      }
      .ma {
        margin-top: 10px;
        font-size: 20px;
      }
      .in input {
        width: 490px;
        height: 30px;
      }
      .bu {
        background-color: #6466e9;
        border-radius: 20px;
        width: 490px;
        height: 35px;
        line-height: 35px;
        margin-top: 50px;
        font-size: 20px;
      }
    }
  }
}</style>
