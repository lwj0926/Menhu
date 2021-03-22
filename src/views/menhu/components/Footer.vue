<template>
  <div class="footer">
    <div class="left">
      <img src="~@/assets/img/footer-logo.png" />
    </div>
    <div class="fgx"></div>
    <div class="mid">
      <p class="up">1996-2018中国科学院计算机网络信息中心 版权所有京ICP备09112257号-94 京公安网备11010802017084号</p>
      <p class="down">Email：support@cnic.cn</p>
    </div>
    <div class="pic">
      <img src="~@/assets/img/btm-right01.png" />
    </div>

    <div class="pic">
      <img src="~@/assets/img/qrcode.png" />
    </div>
  </div>
</template>
<script>
export default {
  name: 'Foot'
}
</script>
<style lang="scss" scoped>
.footer {
  background-color: #373737;
  display: flex;
  height: 140px;
  width: 1920px;
  p {
    margin-left: 5%;
    font-size: 13;
    font-family: Arial, Helvetica, sans-serif;
  }

  .left {
    width: 35%;

    display: flex;
    justify-content: flex-end;
    align-items: center;
  }
  .fgx {
    margin-left: 15px;
    margin-top: 30px;
    margin-bottom: 30px;
    width: 10px;
    border-right: 1px solid #fff;
  }
  .mid {
    width: 34%;
    color: #fff;
    vertical-align: middle;
    margin-right: 8px;
    font-size: 13px;
  }

  .up {
    margin-top: 7%;
    margin-bottom: 0.5%;
  }
  .down {
    margin-top: 0%;
  }
  .pic {
    margin-left: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
  }
}
</style>