<template>
  <div id="app">
    <HeaderDc :navLink="navLink" />
    <MainDc />
    <FooterDc />
  </div>
</template>

<script>
import HeaderDc from "./components/HeaderDc.vue";
import MainDc from "./components/MainDc.vue";
import FooterDc from "./components/FooterDc.vue";

export default {
  name: "App",
  data() {
    return {
      navLink: [
        "CHARACTERS",
        "COMICS",
        "MOVIES",
        "TV",
        "GAMES",
        "COLLECTIBLES",
        "VIDEOS",
        "FANS",
        "NEWS",
        "SHOP",
      ],
    };
  },
  components: {
    HeaderDc,
    MainDc,
    FooterDc,
  },
};
</script>

<style lang="scss">
@import "@/assets/style/resets";

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
