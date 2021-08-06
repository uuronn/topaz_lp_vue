<template>
  <div class="slider">
    <div class="slider__wrapper left">
      <button class="slider__button">←</button>
    </div>
    <ul class="slider__list">
      <li class="slider__item">
        <img class="slider_img" src="../assets/image/slider_talk-img.png" alt="トーク画像">
      </li>
      <li class="slider__item">
        <img class="slider_img" src="../assets/image/slider_group-img.png" alt="集合写真">
      </li>
      <li class="slider__item">
        <img class="slider_img" src="../assets/image/slider_chocolate-img.png" alt="チョコLT">
      </li>
      <li class="slider__item">
        <img class="slider_img" src="../assets/image/slider_talk-img.png" alt="トーク画像">
      </li>
      <li class="slider__item">
        <img class="slider_img" src="../assets/image/slider_group-img.png" alt="集合写真">
      </li>
      <li class="slider__item">
        <img class="slider_img" src="../assets/image/slider_chocolate-img.png" alt="チョコLT">
      </li>
    </ul>
    <div class="slider__wrapper right">
      <button class="slider__button">→</button>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.slider {
  display: flex;
  height: 170px;

  // 矢印ボタンのwrapper
  &__wrapper {
    display: flex;
    position: absolute;
    height: 170px;
    justify-content: center;
    background: $color-white;
  }

  .right {
    right: 0;
  }

  // 矢印ボタン
  &__button {
    margin: auto 8px;
    width: 40px;
    height: 40px;
    border-radius: 50px;
    border: $border-color;
    color: $topaz-dark;
    font-weight: 900;
    transition: 0.5s;

    &:hover {
      border: $border-hover;
      color: $color-white;
      background: $topaz-dark;
      transition: 0.5s;
    }
  }

  // 画像リスト
  &__list {
    display: flex;
    margin: 0 40px;
    list-style: none;
  }
}
</style>
