<template>
  <header>
    <div class="container py-3">
      <div class="row">
        <div class="col-sm-4">
          <div class="logo_wrapper">
            <img src="@/assets/img/dc-logo.png" alt="logo-dc" />
          </div>
        </div>
        <div class="col-sm-8">
          <ul class="row justify-content-between">
            <li v-for="item in navLink" :key="item" class="col-auto">
              <a href="#">
                {{ item }}
              </a>
            </li>
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
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "@/assets/style/variables";
ul {
  padding-top: 39.5px;

  a {
    font-size: 13px;
    font-weight: 700;
    color: $text-color-dark;
    padding-bottom: 54px;
    transition: all 0.25s linear;

    &:hover {
      color: $background-color-blue;
      border-bottom: 5px solid $background-color-blue;
    }
  }
}
</style>