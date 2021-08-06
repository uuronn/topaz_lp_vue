<template>
  <div class="topaz">
    <div class="topaz__container">
      <h1 class="topaz__title">
        <img class="topaz__logo" src="../assets/image/topaz_logo-img.png" alt="トパーズロゴ">
      </h1>
      <p class="topaz__text">エンジニアのinput・outputを可視化する</p>
      <button class="topaz__button">使ってみる!&nbsp;⇀</button>
    </div>
    <TopazImgs/>
  </div>
</template>

<script>
import TopazImgs from './TopazImgs.vue'

export default {
  components: {
    TopazImgs
  }
}
</script>

<style lang="scss" scoped>
.topaz {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 80px -10% 80px 80px;

  &__container {
    text-align: center;
    min-width: 320px;
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

  @media screen and (max-width: 520px) {
    margin: 180px 0 100px 0;

    &__logo {
      width: 120px;
    }

    &__text {
      margin-bottom: 100px;
      text-align: center;
    }
  }
}
</style>
