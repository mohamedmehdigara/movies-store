

<template>

<Fragment>
    <div>Welcome to nuxt.js!</div>
</Fragment>
<Fragment>   
    <nuxt-link to="/product">Product</nuxt-link>
</Fragment>
  </template>

<script>
import Fragment from 'vue-fragment';
Vue.use(Fragment.Plugin);
</script>
