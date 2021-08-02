<template>
  <div class="mv">
    <div class="mv__top">
        <img class="mv__img--logo" src="../assets/image/mv_hackz-img.png" alt="mvハックツのロゴ">
    </div>
    <Topaz/>
    <div class="mv__foot">
      <img class="mv__img--arrow" src="../assets/image/arrow.png" alt="mv矢印画像">
    </div>
  </div>
</template>

<script>
import Topaz from './Topaz.vue'

export default {
  components: {
    Topaz
  }
}
</script>

<style lang="scss" scoped>
.mv {
  background: $topaz-color;

  &__img--logo {
    padding: 2vw 0 0 2vw;
  }

  &__foot {
    text-align: center;
  }
  
}
</style>