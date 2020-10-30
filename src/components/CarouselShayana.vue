<template>
  <section class="hero-section">
    <carousel class="hero-items" :items="1" :nav="false" :autoplay="true">
      <div
        class="single-hero-items set-bg"
        style="background-image: url('/img/hero-1.jpg')"
      >
        <div class="container">
          <div class="row">
            <div class="col-lg-5">
              <span>Bag,kids</span>
              <h1>Indenpenden Day</h1>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
                eiusmod tempor incididunt ut labore et dolore
              </p>
              <a href="#" class="primary-btn">Shop Now</a>
            </div>
          </div>
        </div>
      </div>
      <div
        class="single-hero-items set-bg"
        style="background-image: url('/img/hero-2.jpg')"
      >
        <div class="container">
          <div class="row">
            <div class="col-lg-5">
              <span>Bag,kids</span>
              <h1>Discount Up To 30%</h1>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
                eiusmod tempor incididunt ut labore et dolore
              </p>
              <a href="#" class="primary-btn">Shop Now</a>
            </div>
          </div>
        </div>
      </div>
      <div
        class="single-hero-items set-bg"
        style="background-image: url('/img/pexels6.jpg')"
      >
        <div class="container">
          <div class="row">
            <div class="col-lg-5">
              <span>Bag,kids</span>
              <h1 class="text-white">Nike Air</h1>
              <p class="text-white">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
                eiusmod tempor incididunt ut labore et dolore
              </p>
              <a href="#" class="primary-btn">Shop Now</a>
            </div>
          </div>
        </div>
      </div>
    </carousel>
  </section>
</template>
<script>
import carousel from "vue-owl-carousel";

export default {
  name: "CarouselShayana",
  components: {
    carousel,
  },
};
</script>
