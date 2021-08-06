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

  &__wrapper {
    display: flex;
    position: absolute;
    height: 170px;
    justify-content: center;
    background: $color-white;
  }

  .left {
    left: 0;
  }

  .right {
    right: 0;
  }

  &__list {
    display: flex;
    margin: 0 40px;
    list-style: none;
  }

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
}
</style>
