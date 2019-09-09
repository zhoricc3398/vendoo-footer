<template>
  <div id="app">
    <app-info></app-info>
    <app-category></app-category>
    <app-footer></app-footer>
  </div>
</template>

<script>
import Info from "./components/Info";
import Category from "./components/Category";
import Footer from "./components/Footer";

export default {
  components: {
    appFooter: Footer,
    appCategory: Category,
    appInfo: Info
  }
};
</script>

<style lang="scss"></style>
