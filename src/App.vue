<template>
  <div id="app">
    <HeaderDc />
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
  components: {
    HeaderDc,
    MainDc,
    FooterDc,
  },
};
</script>

<style lang="scss">
// reset
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

a {
  text-decoration: none;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
