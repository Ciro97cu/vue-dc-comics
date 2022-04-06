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
        <div class="row container_logo_dc">
          <div class="col-sm-7">ciao</div>
          <div class="col-sm-5 logo_dc_bg"></div>
        </div>
      </div>
    </div>

    <div class="footer_socials">
      <div class="container">
        <div class="row py-5 align-items-center justify-content-between">
          <div class="col-auto">
            <a class="sign_up_footer" href="#">SIGN-UP NOW</a>
          </div>
          <div class="col-auto">
            <div class="row align-items-center">
              <div class="col-auto follow_footer">FOLLOW US</div>
              <div class="col-auto">
                <img src="../assets/footer-facebook.png" alt="facebook" />
              </div>
              <div class="col-auto">
                <img src="../assets/footer-twitter.png" alt="twitter" />
              </div>
              <div class="col-auto">
                <img src="../assets/footer-youtube.png" alt="youtube" />
              </div>
              <div class="col-auto">
                <img src="../assets/footer-pinterest.png" alt="pinterest" />
              </div>
              <div class="col-auto">
                <img src="../assets/footer-periscope.png" alt="periscope" />
              </div>
            </div>
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
  background-repeat: repeat-x;
}

.container_logo_dc {
  height: 482px;
}

.logo_dc_bg {
  background-image: url(../assets/dc-logo-bg.png);
  background-size: cover;
  background-position: center;
}

.footer_socials {
  background-color: $background-color-dark-grey;
}

.sign_up_footer {
  color: $text-color-white;
  padding: 10px;
  border: 2px solid $background-color-blue;
}

.follow_footer {
  font-size: 20px;
  font-weight: 600;
  color: $background-color-blue;
}
</style>
