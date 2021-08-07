<template>
  <div class="content">
    <ol class="content__list">
      <li class="content__item">
        <ContentItemReverse/>
      </li>
      <li class="content__item">
        <ContentItem/>
      </li>
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
