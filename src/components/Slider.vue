<template>
  <div class="slider">
    <button class="slider__button--left button">←</button>
    <ul class="slider__list">
      <li class="slider__item">
        <img src="../assets/image/slider_talk-img.png" alt="トーク画像">
      </li>
      <li class="slider__item">
        <img src="../assets/image/slider_group-img.png" alt="集合写真">
      </li>
      <li class="slider__item">
        <img src="../assets/image/slider_chocolate-img.png" alt="チョコLT">
      </li>
      <li class="slider__item">
        <img src="../assets/image/slider_talk-img.png" alt="トーク画像">
      </li>
      <li class="slider__item">
        <img src="../assets/image/slider_group-img.png" alt="集合写真">
      </li>
      <li class="slider__item">
        <img src="../assets/image/slider_chocolate-img.png" alt="チョコLT">
      </li>
    </ul>
    <button class="slider__button--right button">→</button>
  </div>
</template>

<style lang="scss" scoped>
.slider {
  display: flex;

  &__button--left {
    left: 0;
  }

  &__button--right {
    right: 0;
  }

  &__list {
    display: flex;
    list-style: none;
  }
  .button {
    position: absolute;
    background: red;
  }

}

</style>
