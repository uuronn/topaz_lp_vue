<template>
  <div class="topaz">
    <div class="topaz__container">
      <h1 class="topaz__title">
        <img class="topaz__logo" src="../assets/image/topaz_logo-img.png" alt="トパーズロゴ">
      </h1>
      <p class="topaz__text">エンジニアのinput・outputを可視化する</p>
      <button class="topaz__button">使ってみる!&nbsp;⇀</button>
    </div>
    <img class="topaz__profile" src="../assets/image/topaz_mix-img.png" alt="プロフィール画像">
    <img class="topaz__sp" src="../assets/image/topaz_profile-img.png" width="220px" height="120px" alt="スマホ版画像">
    <img class="topaz__sp--small" src="../assets/image/topaz_profile-mini-img.png" widht="120px" height="240px" alt="スマホ版画像">
  </div>
</template>

<style lang="scss" scoped>
.topaz {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 80px 0 80px 80px;

  &__container {
    text-align: center;
    min-width: 320px;
    margin-right: 6vw;
    z-index: 8;
  }

  &__logo {
    width: 15vw;
  }

  &__text {
    font-size: 14px;
    font-weight: bolder;
    margin: 2vw 0 4vw 0;
    color: #fff;
    padding-left: 30px;
  }

  &__button {
    background: white;
    color: #29A3BF;
    border: 3px solid #29A3BF;
    border-radius: 50px 0 50px 50px;
    width: 160px;
    height: 40px;
    font-weight: 600;

    &:hover {
      background: #29A3BF;
      border: 3px solid #fff;
      color: #fff;
    }
  }

  &__profile {
    width: 60vw;
    min-width: 320px;
    margin: 0 -10% 0 8vw;
  }

  &__sp {
    display: none;
  }

  &__sp--small {
    display: none;
  }
    
  @media screen and (max-width: 520px) {
    margin: 180px 0 100px 0;

    &__wrapper {
      margin: 0;
    }

    &__logo {
      width: 120px;
    }

    &__text {
      margin-bottom: 100px;
      text-align: center;
    }

    &__profile {
      display: none;
    }
    
    &__sp {
      display: block;
      position: absolute;
      right: -12%;
      top: 10%;
      transform: rotate(-10deg);
      z-index: 7;
    }

    &__sp--small {
      display: block;
      position: absolute;
      left: -5%;
      bottom: -4%;
      transform: rotate(24deg);
      z-index: 7;
    }
  }
}
</style>
