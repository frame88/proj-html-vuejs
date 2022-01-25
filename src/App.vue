<template>
  <div id="app">
    <Header />
    <Jumbotron />
    <MainOne />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Jumbotron from './components/Jumbotron.vue';
import MainOne from './components/MainOne.vue';

export default {
  name: "App",
  components: {
    Header,
    Jumbotron,
    MainOne,
  },
};
</script>

<style lang="scss">
@import "./assets/scss/style.scss"
</style>
