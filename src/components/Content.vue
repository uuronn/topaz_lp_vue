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
    <Slider/>
  </div>
</template>

<script>
import Opus from './Opus.vue'
import Slider from './Slider.vue'

export default {
  components: {
    Opus,
    Slider
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