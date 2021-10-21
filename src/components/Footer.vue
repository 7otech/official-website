<template>
  <div id="footer" class="container-fluid">
    <div class="logo">
      <img src="@/assets/img/logo_white.png" alt="logo图">
    </div>
    <p class="title">七橙智擎</p>
    <p class="address_tel_fax">
      <span>地址：北京市海淀区</span>
    </p>
    <p class="email_wx">
      <span>邮箱：1097692918@qq.com</span>
    </p>
    <p class="copy">
      Copyright &copy; 2021 七橙科技
    </p>
    <p class="copy">
      <a href="https://beian.miit.gov.cn/">京ICP备2021009969号</a>
    </p>
  </div>
</template>
<script>
export default {
  name: "Footer",
  data() {
    return {};
  }
};
</script>
<style scoped>
#footer {
  width: 100%;
  height: 100%;
  color: #fff;
  background: #474747;
  overflow: hidden;
  text-align: center;
}
.logo {
  width: 200px;
  height: 52px;
  margin: 50px auto 20px;
}
#footer .logo img {
  width: 200px;
  height: 52px;
  margin: auto;
}
.title {
  font-size: 25px;
  margin-bottom: 20px;
}
.address_tel_fax {
  color: #d3d3d3;
  font-size: 14px;
  margin: 10px 0;
}
.email_wx {
  color: #d3d3d3;
  font-size: 14px;
}
.copy {
  color: #d3d3d3;
  font-size: 14px;
  margin: 50px 0 10px;
}
@media screen and (max-width: 997px) {
  .title {
    font-size: 20px;
  }
  .address_tel_fax {
    font-size: 12px;
  }
  .email_wx {

  font-size: 12px;
}
.copy {
  font-size: 12px;
  margin: 30px 0 10px;
}
}
</style>

