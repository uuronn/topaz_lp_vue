<template>
  <div class="mv">
    <div class="top">
      <img class="top__img" src="../assets/image/mv_hackz-img.png" alt="mvハックツのロゴ">
    </div>
    <Topaz/>
    <div class="foot">
      <img class="foot__img" src="../assets/image/arrow.png" alt="mv矢印画像">
    </div>
  </div>
</template>

<script>
import Topaz from './Topaz.vue'

export default {
  components: {
    Topaz
  },
  data() {
    return {

    }
  }
}
</script>

<style lang="scss" scoped>
  .mv {
    background: linear-gradient(to right, #29A3BF, #4BCBBB);
  }
</style>