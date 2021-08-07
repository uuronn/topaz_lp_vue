<template>
  <div class="contentItem">
    <div class="contentItem__container">
      <h2 class="contentItem__number">01.</h2>
      <div class="contentItem__texts">
        <h2 class="contentItem__title">日頃のインプットをレシピに</h2>
        <p class="contentItem__text">レシピのそれっぽい説明入れてみて！レシピのそれっぽい説明入れてみて！レシピのそれっぽい説明入れてみて！レシピのそれっぽい説明入れてみて！</p>
        <div class="contentItem__wrapper">
          <button class="contentItem__button">もっと見る</button>
        </div>
      </div>
    </div>
    <img class="contentItem__img" src="../assets/image/content_talk-img.png" alt="トーク画像">
  </div>
</template>

<style lang="scss">

.contentItem {
    display: flex;
    justify-content: space-around;
    flex-direction: row-reverse;
    background: blue;
    margin-bottom: 6vw;
  }

// 子コンポーネントをまとめたスタイル
// .contentItem {
//   display: flex;
//   min-width: 380px;
//   background: red;

//   &__wrapper {
//     display: flex;
//     justify-content: center;
//     align-items: center;
//     height: 120px;
//   }

//   &__button {
//     color: #fff;
//     width: 160px;
//     height: 40px;
//     border-radius: 50px;
//     background: $topaz-color;
//     font-weight: 600;
//     box-shadow: 4px 4px 4px gray;
//     transition: 0.5s;

//     &:hover {
//       box-shadow: none;
//       transition: 0.5s;
//     }
//   }

//   &__img {
//     margin: auto 6vw;
//     width: 50vw;
//     min-width: 160px;
//   }
// }
</style>
