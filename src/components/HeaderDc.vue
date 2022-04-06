<template>
  <header>
    <div class="container py-3">
      <div class="row align-items-center">
        <div class="col-sm-4">
          <div class="logo_wrapper">
            <img src="../assets/dc-logo.png" alt="logo-dc" />
          </div>
        </div>
        <div class="col-sm-8">
          <ul class="row justify-content-between">
            <a v-for="item in listItem" :key="item" class="col-auto" href="#">
              <li>{{ item }}</li>
            </a>
          </ul>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "HeaderDc",
  data() {
    return {
      listItem: [
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
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../variables";
ul {
  a {
    font-size: 13px;
    color: $text-color-dark;
  }
}
</style>
