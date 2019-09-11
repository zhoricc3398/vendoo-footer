<template>
  <div id="app">
    <app-slider></app-slider>
    <app-info></app-info>
    <app-category></app-category>
    <app-footer></app-footer>
  </div>
</template>

<script>
import Info from "./components/Info";
import Category from "./components/Category";
import Footer from "./components/Footer";
import Slider from "./components/Slider";

export default {
  components: {
    appFooter: Footer,
    appCategory: Category,
    appInfo: Info,
    appSlider: Slider
  }
};
</script>

<style lang="scss"></style>
