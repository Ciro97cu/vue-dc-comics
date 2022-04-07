<template>
  <main>
    <div class="jumbotron"></div>
    <div class="container_cards py-5">
      <div class="container-sm">
        <div class="row">
          <CardDc
            v-for="(item, index) in card"
            :key="index"
            :singleCard="item"
          />
        </div>
      </div>
    </div>
  </main>
</template>

<script>
import card from "@/assets/data/card";
import CardDc from "@/components/CardDc.vue";
export default {
  name: "MainDc",
  data() {
    return {
      card,
    };
  },
  components: {
    CardDc,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "@/assets/style/variables";

main {
  .jumbotron {
    background-image: url(@/assets/img/jumbotron.jpg);
    background-size: cover;
    height: 350px;
  }
  .container_cards {
    background-color: $background-color-dark;
  }
}
</style>