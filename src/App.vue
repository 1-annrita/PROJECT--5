<template>
  <div id="app">
    <ProductListOne />
    <ProductListTwo />
  </div>
</template>

<script>
import ProductListOne from "./components/ProductListOne.vue";
import ProductListTwo from "./components/ProductListTwo.vue";

export default {
  components: {
    ProductListOne,
    ProductListTwo,
  },
  name: "app",
  data() {
    return {
            
    };
  },
};
</script>

<style>
body {
  font-family: Ubuntu;
  color:#555
}
</style>
