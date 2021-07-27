<template>
  <div class="mv">
    <div class="mv__topLogo">
      <img class="topLogo__img" src="../assets/image/mv_hackz-img.png" alt="">
    </div>
    <div class="mv__mainContainer">
      <div class="mv__mainForm">
        <div class="mv__mainLogo">
          <img class="mainLogo__img" src="../assets/image/topaz-img.png" alt="">
        </div>
        <p class="mv__text">エンジニアのinput・outputを可視化する</p>
        <button class="mv__btn">使ってみる⇀</button>
      </div>
      <div class="mv__mixSample">
        <img class="mixSample__img" src="../assets/image/mv_mix-img.png" alt="">
      </div>
    </div>
    <div class="mv__bottomArrow">
      <img class="bottomArrow__img" src="../assets/image/arrow.png" alt="">
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {

    }
  }
}
</script>

<style lang="scss" scoped>
.mv {
  background: $topaz-color;
  width: 100%;

  &__topLogo {
    .topLogo__img {
      
    }
  }

  &__mainContainer {
    display: flex;
  }
  .mv__mainLogo {
    .mainLogo__img {

    }
  }
}
</style>