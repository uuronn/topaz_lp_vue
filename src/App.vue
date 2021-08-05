<template>
  <div class="root">
    <Header/>
    <Mv/>
    <Content/>
    <Footer/>
  </div>
</template>
<script>
import Header from './components/Header.vue'
import Mv from './components/Mv.vue'
import Content from './components/Content.vue'
import Footer from './components/Footer.vue'

export default {
  components: {
    Header,
    Mv,
    Content,
    Footer
  }
}
</script>

<style lang="scss" scoped>
.root {
  width: 100%;
  position: relative;
  overflow: hidden;
}
</style>
