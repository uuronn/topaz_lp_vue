<template>
  <div class="opus">
    <h2 class="opus__title">作品一覧</h2>
    <ul class="opus__list">
      <li class="opus__item">
        <img src="../assets/image/opus_cat-img.png" alt="作品画像(猫)">
      </li>
      <li class="opus__item">
        <img src="../assets/image/opus_profile-img.png" alt="作品画像">
      </li>
      <li class="opus__item">
        <img src="../assets/image/opus_profile-img.png" alt="作品画像">
      </li>
      <li class="opus__item">
        <img src="../assets/image/opus_cat-img.png" alt="作品画像(猫)">
      </li>
      <li class="opus__item">
        <img src="../assets/image/opus_cat-img.png" alt="作品画像(猫)">
      </li>
      <li class="opus__item">
        <img src="../assets/image/opus_cat-img.png" alt="作品画像(猫)">
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

    &::after {
      content: "";
      background: #29A3BF;
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

  &__item {
    margin-bottom: 40px;
    box-shadow: 4px 4px 4px gray;
    transition: 0.1s;
    border-radius: 18px;

  &:hover {
    box-shadow: 1px 1px 1px gray;
    transition: 0.1s;
  }
  }
}
</style>
