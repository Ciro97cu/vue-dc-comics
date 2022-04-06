<template>
  <main>
    <div class="container py-5">
      <h1>Content goes Here</h1>
    </div>
  </main>
</template>

<script>
export default {
  name: "MainDc",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../variables";
main {
  background-color: $background-color-dark;
  h1 {
    color: $text-color-white;
  }
}
</style>
