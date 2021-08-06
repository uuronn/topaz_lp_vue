<template>
  <div class="content">
    <ol class="content__list">
      <li class="content__item">
        <div class="content__container">
          <h2 class="content__number">01.</h2>
          <div class="content__texts">
            <h2 class="content__title">日頃のインプットをレシピに</h2>
            <p class="content__text">レシピのそれっぽい説明入れてみて！レシピのそれっぽい説明入れてみて！レシピのそれっぽい説明入れてみて！レシピのそれっぽい説明入れてみて！</p>
            <div class="content__wrapper">
              <button class="content__button">もっと見る</button>
            </div>
          </div>
        </div>
        <img class="content__img" src="../assets/image/content_talk-img.png" alt="トーク画像">
      </li>
      <li class="content__item--bottom">
        <div class="content__container">
          <h2 class="content__number">02.</h2>
          <div class="content__texts">
            <h2 class="content__title">作ったモノをプロジェクトに</h2>
            <p class="content__text">プロジェクトのそれっぽい説明入れてみて！プロジェクトのそれっぽい説明入れてみて！プロジェクトのそれっぽい説明入れてみて！</p>
            <div class="content__wrapper">
              <button class="content__button">もっと見る</button>
            </div>
          </div>
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
  margin: 6vw auto;
  z-index: 9;

  &__item {
    display: flex;
    justify-content: space-around;
    flex-direction: row-reverse;
    margin-bottom: 6vw;
  }

  &__item--bottom {
    display: flex;
    justify-content: space-between;
    margin-bottom: 6vw;
  }

  &__container {
    display: flex;
    min-width: 380px;
  }

  &__wrapper {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 120px;
  }

  &__button {
    color: #fff;
    width: 160px;
    height: 40px;
    border-radius: 50px;
    background: $topaz-color;
    font-weight: 600;
    box-shadow: 4px 4px 4px gray;
    transition: 0.5s;

    &:hover {
      box-shadow: none;
      transition: 0.5s;
    }
  }

  &__img {
    margin: auto 6vw;
    width: 50vw;
    min-width: 160px;
  }

  @media  screen and (max-width: 720px) {
    width: 95%;

    &__item {
      flex-direction: column;
    }

    &__item--bottom {
      flex-direction: column;
    }

    &__container {
      
    }

    &__img {
      margin: auto;
    }
  }
}
</style>
