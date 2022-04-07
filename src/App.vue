<template>
  <div id="app">
    <HeaderDc />
    <MainDc />
    <ProductsDc />
    <FooterDc />
  </div>
</template>

<script>
import HeaderDc from "./components/HeaderDc.vue";
import MainDc from "./components/MainDc.vue";
import ProductsDc from "./components/ProductsDc.vue";
import FooterDc from "./components/FooterDc.vue";

export default {
  name: "App",
  components: {
    HeaderDc,
    MainDc,
    ProductsDc,
    FooterDc,
  },
};
</script>

<style lang="scss">
@import "@/assets/style/resets";

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
</style>
