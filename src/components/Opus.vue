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

  &__title {
    text-align: center;
  }

  &__list {
    display: flex;
    justify-content: space-around;
    flex-wrap:wrap;
    list-style: none;
  }
}
</style>