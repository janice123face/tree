<template>
  <div class="new">
  <p class="xin">{{ msg }}</p>
  <div class="box">
  <div class="screen">
  <select class="sTitle">
  <option class="screenTitle">类别<img src="assets/10.jpg"></option>
</select>
 <select class="sTitle">
  <option class="screenTitle">尺码<img src="assets/10.jpg"></option>
</select>
<select class="sTitle">
  <option class="screenTitle">颜色<img src="assets/10.jpg"></option>
</select>
<select class="scrTitle">
  <option class="screentitleDr">排序<img src="assets/10.jpg"></option>
</select>
  </div>
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
    <img src="../assets/tory心选940(1).jpg">
    <div class="quan">全新系列</div>
    <div class="imm"><a  href="">即刻选购</a></div>
    <div class="home"><a  href="">首页  </a>/<a  href="">用户  </a>/<a  href="">品牌故事</a></div>
   </div>
  </div>
  <div class="clear"></div>
</template>
<script>
export default {
  name: 'NewEditor',
  props: {
    msg: String
  }
}
</script>
<style scoped>
.xin{
  position:relative;
  top:-15px;
  font-size:18px;
}
.box{
   margin:auto;
   width:1250px;
  height:1500px;
}
.screen{
  width:1247px;
  margin-bottom:80px;
}
select{
  width:65px;
  height:50px;
  padding:4px 0;
  border:none;
  display:inline;
}
.sTitle{
float:left;
margin-right:15px;
}
.scrTitle{
float:right;
}
select:hover{
  border-bottom:1px solid #000000;
}
.picture{
  width:1250px;
  height:450px;
  display:flex;
  justify-content:space-between;
  padding-bottom:25px;
}
.product{
  width:310px;
  height:450px;
  float:left;
}
.product a img{
  width:310px;
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
.quan{
  font-style:bold;
  font-size:20px;
  line-height:50px;
}
.imm a{
 font-size:16px;
 color:#000000;
 display:block;
 margin-bottom:10px;
}
.home{
  float:left;
  margin-top:40px;
}
.home a{
color:#000000;
}
</style>
