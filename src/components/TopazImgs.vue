<template>
  <div class="Imgs">
    <img class="Imgs__profile" :src="images.pc" alt="プロフィール画像">
    <img class="Imgs__sp show" :src="images.sp" width="220px" height="120px" alt="スマホ版画像">
    <img class="Imgs__sp--small show" :src="images.spMini" widht="120px" height="240px" alt="スマホ版画像">
  </div>
</template>

<script>
export default {
  data() {
    return {
      images: {
        pc: require("../assets/image/topaz_mix-img.png"),
        sp: require("../assets/image/topaz_profile-img.png"),
        spMini: require("../assets/image/topaz_profile-mini-img.png")
      }
    }
  }
}
</script>

<style lang="scss" scoped>
.Imgs {
  &__profile {
    width: 60vw;
    min-width: 320px;
    margin-left: 13vw;
  }

  .show {
    display: none;
  }

  @media screen and (max-width: 520px) {
    &__profile {
      display: none;
    }

    .show {
      display: block;
      position: absolute;
      z-index: 7;
    }
    
    &__sp {
      right: -12%;
      top: 10%;
      transform: rotate(-10deg);
    }

    &__sp--small {
      left: -5%;
      bottom: -4%;
      transform: rotate(24deg);
    }
  }
}
</style>
