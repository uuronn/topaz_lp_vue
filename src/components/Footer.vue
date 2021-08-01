<template>
  <div class="footer">
    <img class="footer__img" src="../assets/image/footer-img.png" alt="">
    <p class="footer__copy">©2020 Hack’z  Inc. all rights reserved.</p>
  </div>
</template>

<style lang="scss" scoped>
.footer {
  background: #000;
  &__img {
    width: 20vw;
    min-width: 200px;
    margin: 5vw;
  }

  &__copy {
    color: #fff;
    font-size: 8px;
    padding: 0 5vw 5vw 5vw;
  }
}
</style>