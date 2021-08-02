<template>
  <div class="content">
    <div class="container">
      <div>
        <img src="../assets/image/talk-img.png" alt="">
      </div>
      <div>
        日頃
      </div>
    </div>
    <div class="container">

    </div>
    <Opus/>
  </div>
</template>

<script>
import Opus from './Opus.vue'

export default {
  components: {
    Opus
  }
}
</script>


<style lang="scss" scoped>
.content {
  width: 80%;
  background: #eee;
  margin: 0 auto;
}
</style>