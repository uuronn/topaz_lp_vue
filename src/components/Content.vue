<template>
  <div class="content">
    <ol class="content__list">
      <li class="content__item">
        <h2>fdfd</h2>
        <div class="content__container">
          <h2 class="content__title">日頃のインプットをレシピに</h2>
          <p class="content__text">レシピのそれっぽい説明入れてみて！レシピのそれっぽい説明入れてみて！レシピのそれっぽい説明入れてみて！レシピのそれっぽい説明入れてみて！レシピのそれっぽい説明入れてみて！レシピのそれっぽい説明入れてみて！レシピのそれっぽい説明入れてみて！</p>
          <button class="content__button">もっと見る</button>
        </div>
        <img class="content__img" src="../assets/image/content_talk-img.png" alt="トーク画像">
      </li>
      <li class="content__item">
        <div class="content__container">
          <h2 class="content__title">作ったモノをプロジェクトに</h2>
          <p class="content__text">プロジェクトのそれっぽい説明入れてみて！プロジェクトのそれっぽい説明入れてみて！プロジェクトのそれっぽい説明入れてみて！プロジェクトのそれっぽい説明入れてみて！プロジェクトのそれっぽい説明入れてみて！プロジェクトのそれっぽい説明入れてみて！</p>
          <button class="content__button">もっと見る</button>
        </div>
        <img class="content__img" src="../assets/image/content_question-img.png" alt="クエスチョン画像">
      </li>
    </ol>
    <Opus/>
    <Slider/>
  </div>
</template>

<script>
import Opus from './Opus.vue'
import Slider from './Slider.vue'

export default {
  components: {
    Opus,
    Slider
  }
}
</script>


<style lang="scss" scoped>
.content {
  width: 85%;
  background: #eee;
  margin: 0 auto;
  z-index: 9;

  &__item {
    display: flex;
  }
}
</style>
