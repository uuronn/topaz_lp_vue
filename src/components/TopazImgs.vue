<template>
  <div class="topazImgs">
    <img class="topazImgs__pc" :src="images.pc" alt="パソコン版画像">
    <img class="topazImgs__sp show" :src="images.sp" alt="スマホ版画像">
    <img class="topazImgs__sp--small show" :src="images.spMini" alt="スマホ版画像">
  </div>
</template>

<script>
export default {
  data() {
    return {
      images: {
        pc: require("../assets/image/topazImgs_pc-img.png"),
        sp: require("../assets/image/topazImgs_sp-img.png"),
        spMini: require("../assets/image/topazImgs_sp-small-img.png")
      }
    }
  }
}
</script>

<style lang="scss" scoped>
.topazImgs {

  // パソコン版画像
  &__pc {
    width: 60vw;
    min-width: 320px;
    margin-left: 13vw;
  }

  // スマホ版画像のスタイルまとめたもの
  .show {
    display: none;
  }

  @media screen and (max-width: 520px) {
    &__pc {
      display: none;
    }
    
    .show {
      display: block;
      position: absolute;
      z-index: 7;
    }
    
    // スマホ版画像
    &__sp {
      width: 220px;
      height: 120px;
      right: -12%;
      top: 10%;
      transform: rotate(-10deg);
    }

    // スマホ版画像 小さいほう
    &__sp--small {
      width: 120px;
      height: 240px;
      left: -5%;
      bottom: -4%;
      transform: rotate(24deg);
    }
  }
}
</style>
