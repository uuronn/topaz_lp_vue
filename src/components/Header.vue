<template>
  <div class="header" >
    <div class="header__wrapper">
      <img class="header__logo" src="../assets/image/header_logo-img.png" alt="ヘッダー画像">
    </div>
    <button class="header__button">使ってみる⇀</button>
  </div>
</template>

<style lang="scss" scoped>
.header {
  display: flex;
  justify-content: space-between;
  position: fixed;
  z-index: 10;
  background: #fff;
  opacity: 0.5;
  // display: none;
  
  &__logo {
    padding: 2vw 0 1vw 2vw;
  }

  &__button {

  }
}
</style>