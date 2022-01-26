<template>
  <div id="app">
    <Header />
    <Jumbotron />
    <Loghi />
    <MainOne />
    <MainTwo />
    <MainTre />
    <Footer />

  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Jumbotron from './components/Jumbotron.vue';
import Loghi from "./components/Loghi.vue";
import MainOne from './components/MainOne.vue';
import MainTwo from './components/MainTwo.vue';
import MainTre from "./components/MainTre.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Jumbotron,
    Loghi,
    MainOne,
    MainTwo,
    MainTre,
    Footer,
  },
};
</script>

<style lang="scss">
@import "./assets/scss/style.scss";
@import url('https://fonts.googleapis.com/css2?family=Balsamiq+Sans&family=Dongle:wght@700&display=swap');
</style>
