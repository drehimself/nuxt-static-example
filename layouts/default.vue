<template>
  <div class="container font-sans text-black">
    <main-navigation></main-navigation>
    <nuxt />
  </div>
</template>

<script>
import MainNavigation from '../components/MainNavigation'

export default {
  components: {
    MainNavigation
  }
}
</script>


<style>
  .container-inner {
    max-width: 650px;
  }

  .nav.nuxt-link-active {
    font-weight: bold;
    text-decoration: underline;
  }
</style>
