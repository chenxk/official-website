<template>
    <div id="CompanyIntroduction">
        <div class="banner container-fuild text-center">关于我们</div>
        <div class="container">
            <div class="row CompanyIntroduction-container">
                <div class="col-xs-12 col-sm-12 col-md-6 wow zoomIn">
                    <img class="img-responsive center-block" src="@/assets/img/about_img.png">
                </div>
                <div class="col-xs-12 col-sm-12 col-md-6">
                    <h3>广州市诚希信息技术有限公司</h3>
                    <p class=".text-justify">广州市诚希信息技术有限公司成立于2019年11月25日，注册地位于广州市番禺区南村镇博旺街18号1001房。经营范围包括软件开发;信息系统集成服务;数据处理和存储支持服务;数字内容制作服务（不含出版发行）;信息技术咨询服务;图文设计制作;摄像及视频制作服务;互联网销售（除销售需要许可的商品）;商务代理代办服务;非居住房地产租赁;食品互联网销售（销售预包装食品）</p>
                    <p class=".text-justify">我们的客户包括集团上市公司, 酒店, IT科技, 教育, 服装, 贸易, 外贸, 时尚, 生物, 工业, 制造等众多行业, 并树立了良好的口碑, 积累了丰富的经验和成功案例. 我们提供权威专业的互联网品牌策划, 并实施高标准的设计方案, 创造真正意义上的品牌网站, 为互联网品牌在互动行销领域创造最大价值而不懈努力!</p>
                </div>
            </div>
        </div>
      <p>&nbsp;</p>
      <p>&nbsp;</p>
    </div>
</template>
<script>
import { WOW } from 'wowjs';
export default {
    name: 'CompanyIntroduction',
    data(){
        return{

        }
    },
    mounted(){
        var wow = new WOW();
        wow.init();
    }
}
</script>
<style scoped>
.banner{
    color: #fff;
    font-size: 30px;
    height: 150px;
    line-height: 150px;
    background-image: url('../assets/img/banner1.png');
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: scroll;
    background-position: center center;
}
.row{
    margin-right: 0;
    margin-left: 0;
}
.CompanyIntroduction-container{
    padding: 100px 0;
    color: #808080;
    transition: all ease 0.5s;
}
.CompanyIntroduction-container>div>p{
    font-size: 14px;
    line-height: 2.5rem;
}
@media screen and (max-width: 997px){
    .CompanyIntroduction-container{
    padding: 10px 0;
    color: #808080;
}
}
</style>

