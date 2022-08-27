<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <Product/>
  </div>
</template>

<script>
// @ is an alias to /src
import Product from '@/components/product.vue'

export default {
  // name: 'Home',
  components: {
    Product
  }
}
</script>
