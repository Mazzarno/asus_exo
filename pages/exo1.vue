<template>
  <div>
    <vs-row>
      <div class="container">
        <img
          src="~/assets/img/Banniere1.jpg"
          class="banniere1 responsive"
          alt="Vivobook 13 Slate OLED"
        />

        <div class="decouvrir1">
          <vs-button
            size="xl"
            gradient
            warn
            href="https://estore.asus.com/fr/90nb0vc2-m005a0-vivobook-13-slate-oled-t3300.html"
          >
            <p>DÉCOUVRIR</p>
          </vs-button>
        </div>

        <div>
          <a
            href="https://www.ldlc.com/fiche/PB00469315.html"
            target="_blank"
            rel="noopener noreferrer"
          >
            <img src="~/assets/img/LDLC.jpg" class="responsive LDLC zoom" />
          </a>
        </div>

        <div>
          <a
            href="https://www.fnac.com/Pack-PC-portable-2-en-1-Asus-VivoBook-13-Slate-OLED-T3300KA-LQ069W-13-3-Full-HD-tactile-Intel-Pentium-8-Go-RAM-128-Go-SSD-Noir-Housse-stylet/a16314972/w-4#omnsearchpos=1"
            target="_blank"
            rel="noopener noreferrer"
          >
            <img src="~/assets/img/fnac.png" class="responsive fnac zoom" />
          </a>
        </div>

        <div class="">
          <a
            href="https://www.darty.com/nav/achat/informatique/ordinateur_portable-portable/portable/asus_t3300ka-pen_8_28_1.html"
            target="_blank"
            rel="noopener noreferrer"
          >
            <img src="~/assets/img/darty.png" class="responsive darty zoom" />
          </a>
        </div>

        <div class="oled">
          <a
            href="https://www.asus.com/fr/Content/Laptop-OLED/"
            target="_blank"
            rel="noopener noreferrer"
          >
            <img
              src="~/assets/img/oled.webp"
              class="responsive zoom"
              width="100px"
            />
          </a>
        </div>
      </div>
    </vs-row>

    <vs-row align="center" justify="center" :w="12" class="mt">
      <vs-col :w="10">
        <div class="mt"><h1>Vivobook OLED</h1></div>
        <div class="my"><h2>Votre écran OLED</h2></div>
        <div class="mb"><h3>Découvrez l’univers du Vivobook OLED</h3></div>

        <vs-row class="my">
          <vs-col align="center" justify="center" :w="6" class="">
            <div class="mx">
              <img
                @click="popupVid1 = true"
                src="~/assets/img/Video 1.jpg"
                class="zoom responsive"
                width="70%"
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
            <div class="mb">
              <h3>Une touche de liberté - VivoBook S13/S14/S15 | ASUS</h3>
            </div>
          </vs-col>

          <vs-col align="center" justify="center" :w="6">
            <div class="mx">
              <img
                @click="popupVid2 = true"
                src="~/assets/img/Video 2.jpg"
                class="zoom responsive"
                width="70%"
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
            <div class="mb">
              <h3>
                Vivobook 13 Slate OLED - Votre PC. Votre écran OLED. À emporter.
              </h3>
            </div>
          </vs-col>
        </vs-row>
      </vs-col>
    </vs-row>

    <vs-row align="center" justify="center">
      <div class="mb"><h3>Votre écran OLED Personnel</h3></div>
      <div class="container">
        <img
          src="~/assets/img/Banniere2.jpg"
          class="banniere2 responsive"
          alt=""
          srcset=""
        />
        <div class="text_img">
          <p class="text_white">
            Admirez le magnifique écran OLED Dolby Vison® de 13,3 pouces et
            appréciez le son immersif de Dolby Atmos®.
          </p>
          <p class="text_white">
            Le divertissement n'a jamais été aussi portable et personnel !
          </p>
        </div>
        <div class="decouvrir2">
          <vs-button
            size="xl"
            gradient
            warn
            href="https://estore.asus.com/fr/90nb0vc2-m005a0-vivobook-13-slate-oled-t3300.html"
          >
            <p>DÉCOUVRIR</p>
          </vs-button>
        </div>
      </div>
    </vs-row>
    <vs-row class="my" justify="center">
      <div><h2>Découvrez nos PC étudiants</h2></div>
      <vs-row justify="center" class="m_podium">
        <div class="container mt">
          <img width="70%" src="~/assets/img/podium_orange.png" alt="" />
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
                  class="responsive asus_vivobook up"
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
export default {
  data() {
    return {
      popupVid1: false,
      popupVid2: false,
    }
  },
}
</script>