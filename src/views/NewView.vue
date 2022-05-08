<template>
  <div class="new">
  <img src="../assets/08.jpg" class="tu">
  <video class="wei"  src="../assets/Spring.mp4"  autoplay="autoplay" loop="loop" width="1200" height="520"></video>
  <NewEditor msg="全新系列"/>
  </div>
</template>

<script>
import NewEditor from '@/components/NewEditor.vue'
export default {
  name: 'NewView',
  components: {
    NewEditor
  }
}
</script>
<style scoped>
.tu{
  margin:-15px 0 30px 0;
  width:1200px;
}
</style>
