<template>
  <div id="app">
    <!-- NAV DRAWER -->

    <!-- NAV BAR -->
    <vs-navbar>
      <template #left>
        <nuxt-link to="/">
          <div class="logo_asus"></div>
        </nuxt-link>
      </template>
      <vs-navbar-item to="/exo1" id="Exo1"> Exo 1 </vs-navbar-item>
      <vs-navbar-item to="/exo2" id="Exo2"> Exo 2 </vs-navbar-item>
    </vs-navbar>
    <!-- MAIN -->
    <transition name="page" mode="out-in">
      <Nuxt />
    </transition>

    <!-- FOOTER -->
  </div>
</template>

<script>
export default {
  transition: {
    name: 'home',
    mode: 'out-in',
  },
}
</script>
<style>
.page-enter-active,
.page-leave-active {
  transition: opacity 0.5s;
}
.page-enter,
.page-leave-to {
  opacity: 0;
}
</style>