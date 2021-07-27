<template>
  <div class="footer">
    <div class="footer__container">
      <div class="footer__mainLogo">
        <img class="mainLogo__img" src="../assets/image/footer-img.png" alt="">
      </div>
      <div class="footer__wrapper">
        <p class="footer__copy">©2020 Hack’z  Inc. all rights reserved.</p>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.footer {
  background: #000;
  width: 100%;

  &__container {
    padding: 30px 0 30px 30px;
  }

  &__mainLogo {
    margin-bottom: 30px;
    .mainLogo__img {

    }
  }

  &__wrapper {

  }

  &__copy {
    color: #fff;
  }
}
</style>