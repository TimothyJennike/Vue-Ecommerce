<template>
  <navbarVue></navbarVue>
  <router-view/>
  <footerVue></footerVue>
</template>
<script>
import navbarVue from './components/Navbar.vue';
import footerVue from './components/Footer.vue';
import productsVue from './components/Products.vue';
export default {
  components :{
    navbarVue,
    footerVue,
    productsVue
    }
}
</script>

<style>
</style>
