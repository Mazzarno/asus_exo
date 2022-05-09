<template>
  <div id="app">
    <!-- NAV DRAWER -->

    <!-- NAV BAR -->
    <vs-navbar>
      <template #left>
        <nuxt-link to="/">
          <div
            data-aos="flip-up"
            data-aos-duration="1000"
            class="logo_asus"
          ></div>
        </nuxt-link>
      </template>
      <vs-navbar-item
        data-aos="fade-down"
        data-aos-duration="1500"
        to="/exo1"
        id="Exo1"
      >
        Exo 1
      </vs-navbar-item>
      <vs-navbar-item
        data-aos="fade-down"
        data-aos-duration="1500"
        to="/exo2"
        id="Exo2"
      >
        Exo 2
      </vs-navbar-item>
    </vs-navbar>
    <!-- MAIN -->
    <transition name="page" mode="out-in">
      <Nuxt />
    </transition>

    <!-- FOOTER -->
  </div>
</template>

<script>
import aosMixin from '~/mixins/aos'
export default {
  mixins: [aosMixin],
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