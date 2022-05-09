<template>
  <div>
    <vs-row justify="center" align="center" class="mt">
      <vs-col w="10" xs="12">
        <Banniere1SVG data-aos="zoom-in" data-aos-duration="1500" />
      </vs-col>
    </vs-row>
    <vs-row align="center" justify="center" :w="12" class="mt">
      <vs-col :w="10">
        <div class="mt">
          <h1
            data-aos="zoom-in-down"
            data-aos-duration="1500"
            data-aos-delay="500"
            class="h1"
          >
            Vivobook OLED
          </h1>
        </div>
        <div class="my">
          <h2
            data-aos="zoom-in-down"
            data-aos-duration="1500"
            data-aos-delay="1000"
            class="h2"
          >
            Votre écran OLED
          </h2>
        </div>
        <div class="mb">
          <h3
            data-aos="zoom-in-down"
            data-aos-duration="1500"
            data-aos-delay="1500"
            class="h3"
          >
            Découvrez l’univers du Vivobook OLED
          </h3>
        </div>

        <vs-row class="my">
          <vs-col align="center" justify="center" :w="6" xs="12" class="mt">
            <div
              data-aos="fade-right"
              data-aos-duration="1500"
              data-aos-delay="2000"
              class="mx"
            >
              <img
                @click="popupVid1 = true"
                src="~/assets/img/Video 1.jpg"
                class="zoom responsive"
                width="90%"
              />
            </div>

            <vs-dialog width="70%" v-model="popupVid1" blur not-padding>
              <div class="video-responsive">
                <iframe
                  width="100%"
                  height="100%"
                  src="https://www.youtube.com/embed/0sjUjl_7nI8"
                  title="YouTube video player"
                  frameborder="0"
                  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                  allowfullscreen
                ></iframe></div
            ></vs-dialog>
            <div
              data-aos="fade-right"
              data-aos-duration="1500"
              data-aos-delay="2000"
              class="mb"
            >
              <a
                href="https://www.youtube.com/watch?v=0sjUjl_7nI8"
                target="_blank"
                rel="noopener noreferrer"
                ><h3 class="my">
                  Une touche de liberté - VivoBook S13/S14/S15 | ASUS
                </h3></a
              >
            </div>
          </vs-col>

          <vs-col align="center" justify="center" :w="6" xs="12" class="mt">
            <div
              data-aos="fade-left"
              data-aos-duration="1500"
              data-aos-delay="2000"
              class="mx"
            >
              <img
                @click="popupVid2 = true"
                src="~/assets/img/Video 2.jpg"
                class="zoom responsive"
                width="90%"
              />
            </div>

            <vs-dialog width="70%" v-model="popupVid2" blur not-padding>
              <div class="video-responsive">
                <iframe
                  width="100%"
                  height="100%"
                  src="https://www.youtube.com/embed/zIgEaGz_CO4"
                  title="YouTube video player"
                  frameborder="0"
                  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                  allowfullscreen
                ></iframe></div
            ></vs-dialog>
            <div>
              <a
                href="https://www.youtube.com/watch?v=zIgEaGz_CO4"
                target="_blank"
                rel="noopener noreferrer"
              >
                <h3
                  data-aos="fade-left"
                  data-aos-duration="1500"
                  data-aos-delay="2000"
                  class="my"
                >
                  Vivobook 13 Slate OLED - Votre PC. Votre écran OLED. À
                  emporter.
                </h3></a
              >
            </div>
          </vs-col>
        </vs-row>
      </vs-col>
    </vs-row>

    <vs-row align="center" justify="center">
      <div
        data-aos="fade-down"
        data-aos-duration="1500"
        data-aos-delay="2500"
        class="mb"
      >
        <h3>Votre écran OLED Personnel</h3>
      </div>
      <vs-col w="12">
        <Banniere2SVG />
      </vs-col>
    </vs-row>
    <vs-row class="my" justify="center">
      <div><h2>Découvrez nos PC étudiants</h2></div>
      <vs-row justify="center" class="m_podium">
        <div class="container mt">
          <img width="70%" src="~/assets/img/podium_orange.png" />
          <div>
            <a
              href="https://www.asus.com/fr/Laptops/For-Home/Vivobook/"
              target="_blank"
              rel="noopener noreferrer"
            >
              <vs-tooltip top class="asus_vivobook_tooltip">
                <img
                  src="~/assets/img/vivobook PC.png"
                  width="70%"
                  class="responsive asus_vivobook fly"
                />
                <template #tooltip> Parfait pour les étudiants </template>
              </vs-tooltip>
            </a>
          </div>
          <div class="text_podium">
            <p class="p_podium">ASUS Vivobook Pro 15 OLED</p>
          </div>
          <div class="decouvrir3">
            <vs-button
              size="l"
              gradient
              dark
              href="https://www.asus.com/fr/Laptops/For-Home/Vivobook/"
            >
              <p class="text_white">DÉCOUVRIR</p>
            </vs-button>
          </div>
        </div>
      </vs-row>
    </vs-row>
  </div>
</template>

<script>
import Banniere1SVG from '../components/banniere1SVG.vue'
import Banniere2SVG from '../components/banniere2SVG.vue'
import aosMixin from '~/mixins/aos'
export default {
  mixins: [aosMixin],
  data() {
    return {
      popupVid1: false,
      popupVid2: false,
    }
  },
  components: {
    Banniere1SVG,
    Banniere2SVG,
  },
}
</script>