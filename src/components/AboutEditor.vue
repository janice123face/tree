<template>
  <div class="about">
    <p>{{ msg }}</p>
    <div class="middle">
    <b>创造改变</b>
    <p class="text">
“作为一名设计师，我努力创作美丽的系列，以此激发女性保<br/>
持自信、乐观生活。作为一名企业家，我希望无论我们在做什么，<br/>
都始终不忘回馈社会。”—Tory</p>
<div class="pic1"><img src="../assets/image2.jpg"></div>
<p class="texa">每售出一条手链，即向中国妇女发展基金会捐赠200元人民币，<br/>
以支持@她创业计划。</p>
<div class="picture">
  <div class="product">
   <a>
    <img src="../assets/06.jpg">
    <dl>
    <dt>Lee Radziwill 锁缝双层手袋</dt>
    <dd class="row1">￥16,900</dd>
    <dd class="row2">限时满减，每满3000减300元</dd>
    </dl>
    </a>
  </div>
   <div class="product">
   <a>
    <img src="../assets/07.jpg">
    <dl>
    <dt>Lee Radziwill 锁缝双层手袋</dt>
    <dd class="row1">￥16,900</dd>
    <dd class="row2">限时满减，每满3000减300元</dd>
    </dl>
    </a>
  </div>
   <div class="product">
    <a>
    <img src="../assets/09.jpg">
    <dl>
    <dt class>Lee Radziwill 锁缝双层手袋</dt>
    <dd class="row1">￥16,900</dd>
    <dd class="row2">限时满减，每满3000减300元</dd>
    </dl>
    </a>
  </div>
  <div class="product">
    <a>
    <img src="../assets/10.jpg">
    <dl>
    <dt class>Lee Radziwill 锁缝双层手袋</dt>
    <dd class="row1">￥16,900</dd>
    <dd class="row2">限时满减，每满3000减300元</dd>
    </dl>
    </a>
     </div>
    </div>
    <img class="pic3" src="../assets/FINAL_11.jpg">
    <div class="texb">加入我们</div>
    <a class="texc">关注我们的微信</a>
  </div>
  </div>
</template>
<script>
</script>
<style scope>
.middle{
  width:1500px;
  height:2500px;
  margin:auto;
}
b{
  font-size:28px;
}
.text{
   margin-top:-60px;
   line-height:40px;
   }
   .pic1{
     margin-top:120px;
   }
   .texa{
     font-size:20px;
     margin-top:-60px;
     line-height:40px;
   }
   .picture{
  width:1500px;
  height:450px;
  display:flex;
  justify-content:space-between;
  padding-bottom:25px;
  margin:auto;
  margin-top:120px;
}
.product{
  width:370px;
  height:450px;
  float:left;
}
.product a img{
  width:370px;
}
.product dl{
text-align:left;
}
.product dl dt{
font-size:16px;
text-overflow:ellipsis;
}
.product dl dd{
  text-align:left;
  margin-left:0;
color:#dddddd;
line-height:22px;
text-overflow:ellipsis;
}
.pic3{
  margin-top:80px;
}
.texb{
  font-size:27px;
  line-height:68px;
}
.texc{
  text-decoration:underline;
}
</style>
