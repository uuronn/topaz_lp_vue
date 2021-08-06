<template>
  <div class="header" v-show="scrollShow">
    <div class="header__wrapper">
      <img class="header__logo" src="../assets/image/header_logo-img.png" alt="ヘッダー画像">
    </div>
    <button class="header__button">使ってみる!&nbsp;⇀</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      scrollShow: false
    }
  },
  methods: {
    // スクロールしたらヘッダーを表示させるメソッド
    handleScroll() {
      console.log(scrollY)
      if (scrollY > 100) {
        this.scrollShow = true;
      } else {
        this.scrollShow = false;
      }
    }
  },
  
  created() {
    addEventListener("scroll",this.handleScroll)
  }
}
</script>

<style lang="scss" scoped>
.header {
  display: flex;
  justify-content: space-between;
  position: fixed;
  z-index: 10;
  background: $color-white;
  
  &__logo {
    padding: 1vw 0 1vw 2vw;
  }

  // 使ってみる！のボタン
  &__button {
    color: $topaz-dark;
    border: $border-color;
    margin: auto 2vw;
    border-radius: 50px 0 50px 50px;
    font-weight: 600;
    width: 160px;
    height: 40px;
    background: $color-white;

    &:hover {
      color: $color-white;
      border: $border-color;
      background: $topaz-dark;
    }
  }
}
</style>
