<template>
  <div class="user">
  <img src="../assets/Shop_D.jpg" class="pic5">
    <h1>This is an about user</h1>
    <UserEditor msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import UserEditor from '@/components/UserEditor.vue'
export default {
  name: 'UserView',
  components: {
    UserEditor
  }
}
</script>
<style scope>
.user{
  width:1670px;
  margin:auto;border:1px solid red;
}
.pic5{
width:1670px;
}
</style>
