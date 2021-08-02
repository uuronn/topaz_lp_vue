<template>
  <div class="slider">
    <div class="slider__wrapper left">
      <button class="slider__button--left button">←</button>
    </div>
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
    <div class="slider__wrapper right">
      <button class="slider__button--right button">→</button>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.slider {
  display: flex;
  height: 170px;

  &__wrapper {
    position: absolute;
    height: 170px;
    background: red;
    display: flex;
    justify-content: center;
  }

  .left {
    left: 0;
  }

  .right {
    right: 0;
  }

  &__list {
    display: flex;
    list-style: none;
  }
  .button {
    
  }

}

</style>
