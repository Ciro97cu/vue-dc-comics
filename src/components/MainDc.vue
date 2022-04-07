<template>
  <main>
    <div class="jumbotron"></div>
    <div class="container_cards py-5">
      <div class="container-sm">
        <div class="row">
          <div class="cards col-sm-2">
            <div class="card">
              <img src="@/assets/img/jumbotron.jpg" alt="" />
              <p>ACTION COMICS</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
// import CardItem from "@/components/CardItem.vue";
export default {
  name: "MainDc",
  // components: {
  //   CardItem,
  // },
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
    .cards {
      img {
        width: 100%;
      }
    }
  }
}
</style>