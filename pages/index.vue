<template>
  <div>
    <vs-row class="home" justify="center" align="center">
      <vs-button
        data-aos-duration="2000"
        data-aos="zoom-in-right"
        class="mx"
        size="xl"
        to="/exo1"
        animation-type="scale"
        gradient
        >Exercice 1
        <template #animate>
          <span class="mdi mdi-36px mdi-desktop-mac"></span></template
      ></vs-button>

      <vs-button
        data-aos="zoom-in-up"
        data-aos-duration="2000"
        data-aos-delay="1000"
        class="mx"
        size="xl"
        to="/exo2"
        animation-type="scale"
        gradient
        >Exercice 2
        <template #animate>
          <span class="mdi mdi-36px mdi-responsive"></span></template
      ></vs-button>

      <vs-button
        data-aos="zoom-in-down"
        data-aos-duration="2000"
        data-aos-delay="2000"
        animation-type="vertical"
        class="mx"
        size="xl"
        warn
        gradient
        href="https://drive.google.com/file/d/13jN63LoQ5qKEoKSh3zq5qON0aAfTGT75/view"
        blank
        >Wireframe
        <template #animate>
          <span class="mdi mdi-36px mdi-download"></span></template
      ></vs-button>

      <vs-button
        data-aos="zoom-in-left"
        data-aos-duration="2000"
        data-aos-delay="3000"
        class="mx"
        size="xl"
        dark
        gradient
        href="https://github.com/Mazzarno/asus_exo"
        blank
        >Code
        <template #animate>
          <span class="mdi mdi-36px mdi-github"></span></template
      ></vs-button>
    </vs-row>
  </div>
</template>
<script>
</script>