<template>
  <main>
    <div class="jumbotron">
      <div class="tag_series">CURRENT SERIES</div>
    </div>
    <div class="container_cards py-5">
      <div class="container-sm">
        <div class="row">
          <CardDc
            v-for="(item, index) in card"
            :key="index"
            :singleCard="item"
          />
        </div>
        <div class="row mt-5 justify-content-center">
          <div class="col-auto tag_load">LOAD MORE</div>
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

.jumbotron {
  background-image: url(@/assets/img/jumbotron.jpg);
  background-size: cover;
  height: 350px;
  position: relative;

  .tag_series {
    font-size: 16px;
    color: $text-color-white;
    font-weight: 600;
    background-color: $background-color-blue;
    padding: 10px 15px;
    position: absolute;
    bottom: -22px;
    left: 50px;
  }
}

.container_cards {
  background-color: $background-color-dark;

  .tag_load {
    font-size: 16px;
    color: $text-color-white;
    font-weight: 600;
    background-color: $background-color-blue;
    padding: 10px 70px;
  }
}
</style>