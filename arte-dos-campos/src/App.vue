<template>
  <div id="app">
    <Header></Header>
      <router-view></router-view>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';

export default {
  components:{
    Header,
    Footer
  }
}
</script>

<style>
* {
  box-sizing: border-box;
}

body, ul, li, h1, h2, p {
  padding: 0px;
  margin: 0px
}
</style>
