<template>
  <div id="app">
    <Header/>

    <Main :sliderImg="imgSlider"/>

    <Footer/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer,
  }
}
</script>

<style lang="scss">

</style>
