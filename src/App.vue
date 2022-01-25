<template>
  <div id="app">
    <Header />
    <Jumbotron />
    <Loghi />
    <MainOne />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Jumbotron from './components/Jumbotron.vue';
import Loghi from "./components/Loghi.vue";
import MainOne from './components/MainOne.vue';

export default {
  name: "App",
  components: {
    Header,
    Jumbotron,
    Loghi,
    MainOne,
  },
};
</script>

<style lang="scss">
@import "./assets/scss/style.scss"
</style>
