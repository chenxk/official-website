<template>
  <div id="footer" class="container-fluid">
<!--    <div class="logo">
      <img src="@/assets/img/logo2.png" alt="logo图">
    </div>-->
<!--    <p class="title">广州市诚希信息技术有限公司</p>
    <p class="address_tel_fax">
      <span>地址：广州市番禺区南村镇博旺街18号1001房</span>
      <span>Tel：888-888-888</span>
      <span>Fax：8888-88888888</span>
    </p>-->
<!--    <p class="email_wx">
      <span>邮箱：liyunkun_11@163.com</span>
      <span>公司微信号：ilyk_gg</span>
    </p>-->
    <p class="copy">公司地址: 广州市番禺区南村镇博旺街18号1001房</p>
    <p class="copy">Copyright &copy;2022 广州市诚希信息技术有限公司</p>
    <a href="https://beian.miit.gov.cn/#/Integrated/index" target="_blank" style="color: #d3d3d3;"
    >&nbsp;&nbsp;粤ICP备2021124324号-1&nbsp;</a
    >
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
  width: 95px;
  height: 45px;
  margin: 50px auto 20px;
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

