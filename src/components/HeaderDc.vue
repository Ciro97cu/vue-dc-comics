<template>
  <header>
    <div class="container py-4">
      <div class="row align-items-center">
        <div class="col-sm-4">
          <div class="logo_wrapper">
            <img src="../assets/dc-logo.png" alt="logo-dc" />
          </div>
        </div>
        <div class="col-sm-8">
          <ul class="row">
            <a class="col-auto" href="#">
              <li>CHARACTERS</li>
            </a>
            <a class="col-auto" href="#">
              <li>COMICS</li>
            </a>
            <a class="col-auto" href="#">
              <li>MOVIES</li>
            </a>
            <a class="col-auto" href="#">
              <li>TV</li>
            </a>
            <a class="col-auto" href="#">
              <li>GAMES</li>
            </a>
            <a class="col-auto" href="#">
              <li>COLLECTIBLES</li>
            </a>
            <a class="col-auto" href="#">
              <li>VIDEOS</li>
            </a>
            <a class="col-auto" href="#">
              <li>FANS</li>
            </a>
            <a class="col-auto" href="#">
              <li>NEWS</li>
            </a>
            <a class="col-auto" href="#">
              <li>SHOP</li>
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
