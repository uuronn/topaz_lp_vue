<template>
  <div class="topaz">
    <div class="topaz__wrapper">
      <h1 class="topaz__title">
        <img class="topaz__img--logo" src="../assets/image/topaz_logo-img.png" alt="トパーズロゴ">
      </h1>
      <p class="topaz__text">エンジニアのinput・outputを可視化する</p>
      <button class="topaz__btn">使ってみる⇀</button>
    </div>
    <img class="topaz__img--profile" src="../assets/image/topaz_mix-img.png" alt="">
  </div>
</template>

<style lang="scss" scoped>
.topaz {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 80px 0 80px 80px;

  &__wrapper {
    text-align: center;
    min-width: 320px;
    margin-right: 8vw;
  }

  &__img--logo {
    width: 15vw;
  }

  &__text {
    font-size: 12px;
    margin: 2vw 0 4vw 0;
  }

  &__img--profile {
    width: 60vw;
    min-width: 320px;
    margin-right: -10%;
  }
    
  @media screen and (max-width: 480px) {
    margin: 80px 0;

    &__wrapper {
      margin: 0;
    }

    &__img--logo {
      width: 120px;
    }

    &__text {
      margin: 0 0 40px 0;
    }

    &__img--profile {
      display: none;
    }
  }
}
</style>
