<template>
  <div class="home">
  <video class="wei"  src="../assets/Hero.mp4"  autoplay="autoplay" loop="loop" width="1200" height="520"></video>
    <h5>Tory Burch于2004年在纽约成立，是一个具有全球视野的美国奢华时尚生活方式品牌。 公司帮助</h5>
    <h5 class="row" >女性追求创业梦想，并以此捍卫女性权益。</h5>
    <img src="../assets/01.jpg" width="1200">
    <dl>
        <dt>女性</dt>
        <dd>从 Tory 建立她的时尚帝国起，她便一直思考计划应该如何回馈社会并为女性提供支持。  </dd>
        <dd>2009年，她创办了 Tory Burch 基金会，通过提供资金来源、教育和线上资源的形式来帮助女性追求创业梦想， 并以此捍卫  </dd>
        <dd>女性权益，打破外界对于女性的刻板印象。  </dd>
    </dl>
    <img src="../assets/02.jpg" width="1200">
    <HelloWorld msg="时装系列"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
<style scope>
 .wei{margin-top:-40px;
 margin-bottom:18px;
 }
 h5{
   margin-top:-15px;
 }
 dt{ font-size:30px;}
 dd{ font-size:14px;line-height:30px;text-align:center;}
</style>
