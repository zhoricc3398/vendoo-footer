<template>
  <div id="app">
    <product-slider></product-slider>
    <home-info></home-info>
    <home-category></home-category>
    <main-footer></main-footer>
  </div>
</template>

<script>
import HomeInfo from "./components/HomeInfo";
import HomeCategory from "./components/HomeCategory";
import MainFooter from "./components/MainFooter";
import ProductSlider from "./components/ProductSlider";

export default {
  components: {
    MainFooter,
    HomeCategory,
    HomeInfo,
    ProductSlider
  }
};
</script>

<style lang="scss"></style>
