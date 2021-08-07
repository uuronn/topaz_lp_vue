<template>
  <div class="content">
    <ol class="content__list">
      <ContentItemReverse/>
      <ContentItem/>
    </ol>
    <Opus/>
    <Slider/>
  </div>
</template>

<script>
import ContentItemReverse from './ContentItemReverse.vue'
import ContentItem from './ContentItem.vue'
import Opus from './Opus.vue'
import Slider from './Slider.vue'

export default {
  data() {
    return {

    }
  },
  components: {
    ContentItemReverse,
    ContentItem,
    Opus,
    Slider
  }
}
</script>

<style lang="scss">
.content {
  width: 85%;
  margin: 6vw auto;
  z-index: 9;

  // &__item {
  //   display: flex;
  //   justify-content: space-around;
  //   flex-direction: row-reverse;
  //   margin-bottom: 6vw;
  // }
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
</style>
