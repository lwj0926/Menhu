<template>
  <div class="menhu">
    <div class="header">
      <header-group></header-group>
    </div>

    <div class="first">
      <div class="title">
        基础资源
        <div class="line"></div>
      </div>
      <div class="card-con">
        <div class="card">
          <router-link to="/detail?product=hs">
            <img src="~@/assets/img/bgimg/1-1.png" />
            <p>雄安超级计算机</p>
          </router-link>
        </div>
        <div class="card">
          <router-link to="/detail?product=xiongan">
            <img src="~@/assets/img/bgimg/1-2.png" />
            <p>PIDB</p>
          </router-link>
        </div>
        <div class="card">
          <router-link to="/detail?product=pack">
            <img src="~@/assets/img/bgimg/1-3.png" />
            <p>PackOne</p>
          </router-link>
        </div>
        <div class="card">
          <router-link to="/detail?product=piflow">
            <img src="~@/assets/img/bgimg/1-4.png" />
            <p>PiFlow</p>
          </router-link>
        </div>
        <div class="card">
          <router-link to="/detail?product=tongyi">
            <img src="~@/assets/img/bgimg/2-1.png" />
            <p>统一安全管控平台</p>
          </router-link>
        </div>
        <div class="card">
          <router-link to="/detail?product=hs">
            <img src="~@/assets/img/bgimg/2-2.png" />
            <p>文件存储</p>
          </router-link>
        </div>
        <div class="card">
          <router-link to="/detail?product=hs">
            <img src="~@/assets/img/bgimg/2-3.png" />
            <p>人工智能平台</p>
          </router-link>
        </div>
        <div class="card">
          <router-link to="/detail?product=hs">
            <img src="~@/assets/img/bgimg/2-4.png" />
            <p>超级计算平台</p>
          </router-link>
        </div>
      </div>
    </div>
    <div class="second">
      <div class="title">
        应用软件
        <div class="line"></div>
      </div>
      <div class="icon">
        <div class="icon-card">
          <router-link to="/detail?product=xiongan">
            <img src="~@/assets/img/iconimg/01tensorflow.png" />
            <p>Tensorflow</p>
          </router-link>
        </div>
        <div class="icon-card">
          <router-link to="/detail?product=xiongan">
            <img src="~@/assets/img/iconimg/02PyTorch.png" />
            <p>PyTorch</p>
          </router-link>
        </div>
        <div class="icon-card">
          <router-link to="/detail?product=xiongan">
            <img src="~@/assets/img/iconimg/03Sonnet.png" />
            <p>Sonnet</p>
          </router-link>
        </div>
        <div class="icon-card">
          <router-link to="/detail?product=xiongan">
            <img src="~@/assets/img/iconimg/04mxnet.png" />
            <p>Mxnet</p>
          </router-link>
        </div>
        <div class="icon-card">
          <router-link to="/detail?product=xiongan">
            <img src="~@/assets/img/iconimg/05Keras.png" />
            <p>Keras</p>
          </router-link>
        </div>
        <div class="icon-card">
          <router-link to="/detail?product=xiongan">
            <img src="~@/assets/img/iconimg/06Lasagne.png" />
            <p>Lasagne</p>
          </router-link>
        </div>

        <div class="icon-card">
          <router-link to="/detail?product=xiongan">
            <img src="~@/assets/img/iconimg/07caffe.png" />
            <p>Caffe</p>
          </router-link>
        </div>
        <div class="icon-card">
          <router-link to="/detail?product=xiongan">
            <img src="~@/assets/img/iconimg/Abinit.png" />
            <p>Abinit</p>
          </router-link>
        </div>
      </div>
    </div>

    <foot></foot>
  </div>
</template>

<script>
import Foot from './components/Footer'
import HeaderGroup from './components/HeaderGroup'
export default {
  components: {
    Foot,
    HeaderGroup
  },
  methods: {}
}
</script>

<style lang="scss" scoped>
.menhu {
  width: 1920px;
  margin: 0;
  display: flex;
  justify-content: space-between;
  flex-direction: column;
}
.header {
  background-image: url(~@/assets/img/banner.jpg);
  height: 600px;
  background-position: center center;
  background-repeat: no-repeat;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  background-size: 100%;
}

.first {
  height: 600px;
  text-align: center;
  display: flex;
  flex-direction: column;
}
.card-con {
  margin-left: 360px;
  margin-right: 360px;
  margin-bottom: 40px;
  height: 440px;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
}
.card {
  height: 180px;
  width: 255px;
  margin-top: 20px;
  margin-right: 0px;
  margin-left: 0px;

  p {
    margin-top: 5px;
  }
  img {
    box-shadow: 0px 0px 20px 3px #aaa;
    &:hover {
      box-shadow: 0px 0px 20px 3px #999;
    }
  }
}
.second {
  height: 360px;
  background-color: #ecf0fb;
  text-align: center;
}
.icon {
  margin-left: 360px;
  margin-right: 360px;
  margin-bottom: 10px;
  margin-top: 10px;
  height: 160px;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  .icon-card {
    height: 160px;
    width: 100px;
    margin-top: 0%;
    img {
      height: 100px;
      width: 100px;
      box-shadow: 0px 0px 20px 3px #aaa;
      border-radius: 15px;
      object-fit: cover;
    }
  }
}
p {
  vertical-align: middle;
}
.title {
  width: 100%;
  height: 160px;
  text-align: center;
  font-size: 20px;
  font-weight: bold;

  line-height: 140px;
}
.line {
  position: relative;
  top: -45px;
  height: 2px;
  width: 150px;
  margin-top: 1px;
  margin-left: 46%;
  border: 0px;
  background-color: #ecf0fb;
  background-image: linear-gradient(to right, rgba(161, 159, 159, 0), rgba(73, 156, 170, 0.6), rgba(161, 159, 159, 0));
  //background-image: linear-gradient(to right, rgb(187, 182, 182), rgb(35, 125, 177), rgb(245, 241, 241));
}
</style>
