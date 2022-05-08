<template>
  <div class="about">
    <div class="text1">我们的使命 ：女性赋能</div>
    <img src="../assets/BrandPurpose_Tory_desktop.jpg">
    <div class="text2">“女性赋能始终是我追求的梦想和愿景。让女性获得平等权利是人文的一大进步。”—Tory</div>
    <img src="../assets/bigbigpc赋能女性文案(1).jpg">
    <AboutEditor msg="kkkkkkkkkkk"/>
  </div>
</template>

<script>
import AboutEditor from '@/components/AboutEditor.vue'
export default {
  name: 'AboutView',
  components: {
    AboutEditor
  }
}
</script>
<style scope>
.text1{
  font-size:30px;
  line-height:90px;
}
.text2{
  font-size:20px;
  line-height:60px;
}
</style>
