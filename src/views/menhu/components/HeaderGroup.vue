<template>
  <div class="header-group">
    <div class="box">
      <div class="logo"><router-link to="/">先进计算与数据共享服务门户</router-link></div>
      <div class="mid">今天已为<span v-text="1596"></span> 位用户服务</div>
      <el-button type="primary"><router-link to="/login">登录</router-link></el-button>
    </div>
  </div>
</template>
<script>
export default {
  name: 'HeaderGroup'
}
</script>
<style lang="scss" scoped>
.header-group {
  height: 60px;
  width: 1920px;
  background-color: rgba($color: #3d447e, $alpha: 0.5);
  .box {
    margin-left: 360px;
    margin-right: 360px;
    width: 1200px;
    height: 60px;
    display: flex;
  }
  .logo {
    color: #ecf0fb;
    font-family: '隶书';
    font-size: 22px;
    font-weight: bold;
    width: 948px;

    line-height: 60px;
  }
  .mid {
    color: #ecf0fb;
    font-family: 微软雅黑;
    font-size: 14px;
    line-height: 60px;
    width: 200px;
    span {
      color: #d78317;
      font-weight: 700;
      padding: 0 4px;
    }
  }
  .el-button {
    font-size: 14px;
    font-family: 微软雅黑;
    margin: 15px 10px;
    //cursor: pointer;
  }
}
</style>