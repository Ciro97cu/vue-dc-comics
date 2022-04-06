<template>
  <footer>
    <div class="container_bg_blue">
      <div class="container">
        <div class="row py-5 justify-content-between">
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
              <img src="../assets/buy-comics-digital-comics.png" alt="" />
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
              <img src="../assets/buy-comics-merchandise.png" alt="" />
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
              <img src="../assets/buy-comics-subscriptions.png" alt="" />
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
              <img src="../assets/buy-comics-shop-locator.png" alt="" />
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
                src="../assets/buy-dc-power-visa.svg"
                alt=""
              />
            </div>
            DIGITAL COMICS
          </div>
        </div>
      </div>
    </div>
    <div class="jumbo_footer">
      <div class="container">
        <div class="row">
          <div class="col-sm-7"></div>
          <div class="col-sm-5">
            <img src="../assets/dc-logo-bg.png" alt="" />
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterDc",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../variables";

.container_bg_blue {
  background-color: $background-color-blue;
}

.container_footer_images {
  color: $text-color-white;
  column-gap: 10px;
}
.wrapper_footer_images {
  height: 50px;
  img {
    height: 100%;
  }
  .special_image {
    height: 65%;
  }
}
.jumbo_footer {
  background-image: url(../assets/footer-bg.jpg);
  height: 482px;
  .col-sm-5 {
    height: 482px;
    img {
      height: 100%;
    }
  }
}
</style>
