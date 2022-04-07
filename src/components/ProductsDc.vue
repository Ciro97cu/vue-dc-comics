<template>
  <div class="container_bg_blue">
    <div class="container">
      <div class="row py-5 justify-content-around">
        <div
          class="
            col-auto
            d-flex
            flex-direction-row
            align-items-center
            container_footer_images
          "
        >
          <div class="wrapper_footer_images">
            <img src="@/assets/img/buy-comics-digital-comics.png" alt="" />
          </div>
          DIGITAL COMICS
        </div>
        <div
          class="
            col-auto
            d-flex
            flex-direction-row
            align-items-center
            container_footer_images
          "
        >
          <div class="wrapper_footer_images">
            <img src="@/assets/img/buy-comics-merchandise.png" alt="" />
          </div>
          DC MERCHANDISE
        </div>
        <div
          class="
            col-auto
            d-flex
            flex-direction-row
            align-items-center
            container_footer_images
          "
        >
          <div class="wrapper_footer_images">
            <img src="@/assets/img/buy-comics-subscriptions.png" alt="" />
          </div>
          SUBSCRIPTION
        </div>
        <div
          class="
            col-auto
            d-flex
            flex-direction-row
            align-items-center
            container_footer_images
          "
        >
          <div class="wrapper_footer_images">
            <img src="@/assets/img/buy-comics-shop-locator.png" alt="" />
          </div>
          COMIC SHOP LOCATOR
        </div>
        <div
          class="
            col-auto
            d-flex
            flex-direction-row
            align-items-center
            container_footer_images
          "
        >
          <div
            class="
              wrapper_footer_images
              d-flex
              flex-direction-row
              align-items-center
            "
          >
            <img
              class="special_image"
              src="@/assets/img/buy-dc-power-visa.svg"
              alt=""
            />
          </div>
          DC POWER VISA
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ProductsDc",
};
</script>

<style scoped lang="scss">
@import "@/assets/style/variables";

.container_bg_blue {
  background-color: $background-color-blue;

  .container_footer_images {
    color: $text-color-white;
    column-gap: 10px;

    .wrapper_footer_images {
      height: 50px;
      img {
        height: 100%;
      }
      .special_image {
        height: 65%;
      }
    }
  }
}
</style>