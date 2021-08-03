<template>
  <div class="mv">
    <div class="mv__head">
        <img class="mv__logo" src="../assets/image/mv_logo-img.png" alt="ハックツロゴ画像">
    </div>
    <Topaz/>
    <div class="mv__foot">
      <img class="mv__arrow" src="../assets/image/mv_arrow-img.png" alt="矢印の画像">
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

  &__head {
    background: red;
  }

  &__logo {
    padding: 2vw 0 1vw 2vw;
  }

  &__foot {
    text-align: center;
  }
}
</style>
