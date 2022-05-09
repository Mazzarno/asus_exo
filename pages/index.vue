<template>
  <div>
    <vs-row class="home" justify="center" align="center">
      <vs-button class="mx" size="xl" to="/exo1" animation-type="scale" gradient
        >Exercice 1
        <template #animate>
          <span class="mdi mdi-36px mdi-desktop-mac"></span></template
      ></vs-button>

      <vs-button class="mx" size="xl" to="/exo2" animation-type="scale" gradient
        >Exercice 2
        <template #animate>
          <span class="mdi mdi-36px mdi-responsive"></span></template
      ></vs-button>
      <vs-button
        class="mx"
        size="xl"
        to="/exo2"
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
export default {}
</script>