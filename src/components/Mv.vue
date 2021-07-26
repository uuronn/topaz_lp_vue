<template>
  <div class="mv">
    <div class="wrapper">
      <img class="fdfd" src="../assets/image/mv_hackz-img.png" alt="">
    </div>
    <div class="container">
      <div>
        <div>
          <img src="../assets/image/topaz-img.png" alt="">
        </div>
        <p>エンジニアのinput・outputを可視化する</p>
        <button>使ってみる⇀</button>
      </div>
      <div>
        <img src="../assets/image/mv_mix-img.png" alt="">
      </div>
    </div>
    <div></div>
    <div class="mv__wrapper">
      <img src="../assets/image/arrow.png" alt="">
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {

    }
  }
}
</script>

<style lang="scss" scoped>
.mv {
  background: $topaz-color;
  width: 100%;
}

.container {
  display: flex;
}

.mv__wrapper {
  display: flex;
  flex-direction: column-reverse;
  img {
    width: 200px;
  }
}
</style>