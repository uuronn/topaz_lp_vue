<template>
  <div class="footer">
    <img class="footer__img" src="../assets/image/footer_logo-img.png" alt="ハックツロゴ">
    <p class="footer__copy">{{ copy }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      copy: "©2020 Hack’z  Inc. all rights reserved."
    }
  }
}
</script>


<style lang="scss" scoped>
.footer {
  background: $color-black;
  
  &__img {
    width: 20vw;
    min-width: 200px;
    margin: 5vw;
  }

  &__copy {
    color: $color-white;
    font-size: 8px;
    padding: 0 5vw 5vw 5vw;
  }
}
</style>
