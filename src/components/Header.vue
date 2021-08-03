<template>
  <div class="header" >
    <div class="header__wrapper">
      <img class="header__logo" src="../assets/image/header_logo-img.png" alt="ヘッダー画像">
    </div>
    <button class="header__button">使ってみる!&nbsp;⇀</button>
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
    padding: 1vw 0 1vw 2vw;
  }

  &__button {
    margin: auto 2vw;
    background: white;
    color: #29A3BF;
    border: 3px solid #29A3BF;
    border-radius: 50px 0 50px 50px;
    width: 160px;
    height: 40px;
    font-weight: 600;

    &:hover {
      background: #29A3BF;
      border: 3px solid #fff;
      color: #fff;
    }
  }
}
</style>