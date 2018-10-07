<template>
    <div class="work">
    <Card class="list"  >
        <p slot="title" >
           巨星皮肤托管中心
        </p>
        <p>
           微商城项目，对微商城项目进行维护和二次开发，项目地址为公众号《superstar巨星》。兼具传统的微商城的所有功能，相比传统的微商城项目多了三级分销的功能，还有促销活动功能。
        </p>
    </Card>
        <Card class="list"  >
        <p slot="title" >
           晨路查询
        </p>
        <p>
            微信小程序项目，本人独立开发的小程序，采用了wxml+wxss实现前端静态页面，后台采用php，数据库mysql。项目地址为微信小程序《晨路查询》。
        </p>
    </Card>
     <Card class="list"  >
        <p slot="title" >
           千寻网络
        </p>
        <p>
            pc端项目，响应式pc站，主要应用了响应式布局。项目的地址为：http://www.qx1688.net
        </p>
    </Card>
     <Card class="list"  >
        <p slot="title" >
            医美通后台管理系统
        </p>
        <p>
            pc端项目，为传统门店提供更有力的管理方式，极大地提高了传统门店的工作效率。提供财务的计算，包含支付金额的分类。此项目是本地项目没有上线。
        </p>
    </Card>
     <Card class="list"  >
        <p slot="title" >
           返回
        </p>
        <p>
            <router-link to="/">
    <div class="back"><Icon type="md-arrow-round-back" /></div>
    </router-link>
        </p>
    </Card>
    
    
            
    </div>
</template>
<script>
export default {
  name: "work",
  data(){
      return{

      }
      
  },
  methods:{

  }
};
</script>

<style lang="less" scoped>
@fcolor : #285aa5;
@bgcolor :rgba(255, 255, 255, 0.7);
@bgborder : rgba(255, 255, 255, 0.1);
.work {
  width: 80%;
  min-width: 800px;
  margin: 30px auto;
  display: flex;
  flex-wrap:wrap;
  justify-content: center;
  .list{
      width: 350px;
     margin: 20px;
     transition: all .5s linear;
     -webkit-animation: float ease-in-out 2s infinite;
    animation: float ease-in-out 2s infinite;
  }
  .fz{
      font-size: 14px;
      margin: 5px 0;
  }
   a {
    color: #333;
  }
  .back {
    margin: 5px 10px;
    width: 50px;
    height: 50px;
    font-size: 30px;
    text-align: center;
    line-height: 50px;
    border-radius: 8px;
    transition: all 0.3s linear;
  }
  .back:hover {
    background-color: rgba(255, 255, 255, 0.4);
    color: @fcolor;
  }
}
@-webkit-keyframes float {
  0% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
  }
  50% {
    -webkit-transform: translateY(-20px);
    transform: translateY(-20px);
  }
  100% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
  }
}

@keyframes float {
  0% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
  }
  50% {
    -webkit-transform: translateY(-20px);
    transform: translateY(-20px);
  }
  100% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
  }
}
</style>


