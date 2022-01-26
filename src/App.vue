<template>
  <div id="app">
    <Header />
    <Jumbotron />
    <Loghi />
    <MainOne />
    <MainTwo />
    <MainTre />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Jumbotron from './components/Jumbotron.vue';
import Loghi from "./components/Loghi.vue";
import MainOne from './components/MainOne.vue';
import MainTwo from './components/MainTwo.vue';
import MainTre from "./components/MainTre.vue";

export default {
  name: "App",
  components: {
    Header,
    Jumbotron,
    Loghi,
    MainOne,
    MainTwo,
    MainTre,
  },
};
</script>

<style lang="scss">
@import "./assets/scss/style.scss"
</style>
