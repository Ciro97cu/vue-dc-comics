<template>
  <div class="col-sm-2">
    <div class="wrapper_img">
      <img class="pt-5 pb-3" :src="singleCard.thumb" alt="" />
    </div>
    <p>{{ singleCard.series }}</p>
  </div>
</template>

<script>
export default {
  name: "CardDc",
  props: {
    singleCard: Object,
  },
};
</script>

<style lang="scss" scoped>
@import "@/assets/style/variables";
p {
  color: $text-color-white;
}

img {
  width: 100%;
}
</style>