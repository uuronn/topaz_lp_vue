<template>
  <div class="topaz">
    <div class="topaz__wrapper">
      <img class="topaz__img--logo" src="../assets/image/topaz-img.png" alt="">
      <p class="topaz__text">エンジニアのinput・outputを可視化する</p>
      <button class="topaz__btn">使ってみる⇀</button>
    </div>
    <img class="topaz__img--profile" src="../assets/image/mv_mix-img.png" alt="">
  </div>
</template>

<style lang="scss" scoped>
.topaz {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 6vw 0 6vw 6vw;

  &__wrapper {
    text-align: center;
  }

  &__img--logo {
    // width 117 height 150
  }

  &__img--profile {
    width: 60vw;
    min-width: 320px;
  }

}
</style>
