<template>
  <div class="opus">
    <h2 class="opus__title">作品一覧</h2>
    <ul class="opus__list">
      <li class="opus__item">
        <img class="opus__img" src="../assets/image/opus_cat-img.png" alt="作品画像(猫)">
      </li>
      <li class="opus__item">
        <img class="opus__img" src="../assets/image/opus_profile-img.png" alt="作品画像">
      </li>
      <li class="opus__item">
        <img class="opus__img" src="../assets/image/opus_profile-img.png" alt="作品画像">
      </li>
      <li class="opus__item">
        <img class="opus__img" src="../assets/image/opus_cat-img.png" alt="作品画像(猫)">
      </li>
      <li class="opus__item">
        <img class="opus__img" src="../assets/image/opus_cat-img.png" alt="作品画像(猫)">
      </li>
      <li class="opus__item">
        <img class="opus__img" src="../assets/image/opus_cat-img.png" alt="作品画像(猫)">
      </li>
    </ul>
  </div>
</template>

<style lang="scss" scoped>
.opus {
  margin-bottom: 80px;

  &__title {
    text-align: center;
    margin-bottom: 24px;

    // タイトルの下線
    &::after {
      content: "";
      background: $topaz-dark;
      width: 88px;
      border-radius: 50px;
      height: 4px;
      margin: 0 auto;
      display: block;
    }
  }

  &__list {
    display: flex;
    justify-content: space-around;
    flex-wrap:wrap;
    list-style: none;
  }

  // 各作品
  &__item {
    margin-bottom: 40px;
    box-shadow: $opus-shadow;
    transition: 0.1s;
    border-radius: 18px;
    
    &:hover {
      box-shadow: $opus-hover;
      transition: 0.1s;
    }
  }
}
</style>
