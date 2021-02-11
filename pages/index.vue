<template>
  <div>
    <v-container>
      <v-row justify="center" align="center">
        <v-col cols="12" xl="8" sm="8" md="6">
          <div class="text-center">
            <h2 class="display-2">Nous sommes une agence d'inspection d'ouvrage.</h2>
          </div>
        </v-col>
        <v-col cols="12" xl="7" sm="8" md="6">
          <div class="text-center">
            <p class="headline text--disabled">Nous aidons les entreprises à se développer, à lancer des produits et à établir des relations durables avec leurs clients.</p>
            <p class="headline text--disabled">UAScans est une agence de services de drone spécialisée dans les solutions industrielles. Nous utilisons les dernières technologies de pointe en matière de drones.</p>
            <p><a href="">Voir nos Solutions</a></p>
          </div>
        </v-col>
      </v-row>
    </v-container>
   <v-container class="white">
      <v-row justify="center" align="center">
        <v-col class="black--text" cols="12" xl="8" sm="8" md="6">
          <div class="text-right">
            <h3 class="headline bold text-uppercase">Plus que des pilotes de haut niveau</h3>
            <p class="text-black headline light ae-2">Notre équipe n'est pas seulement composée de pilotes certifiés de drones, mais d'experts dans leur domaine et passionnés par la livraison de résultats de qualité.</p>
          </div>
        </v-col>
      </v-row>
    </v-container>
    <v-container class="white">
      <v-row class="black--text" justify="center" align="center">
        <v-col cols="12" xl=" " sm="8" md="6">
          <div class="left">
            <img src="assets/img/video-17.jpg" alt="Stratégie">
          </div>
        </v-col>
        <v-col cols="12" xl="4" sm="8" md="6">
          <div>
            <h2 class="display-2 font-weight-light">Aesthetic isn't simply about good design</h2>
            <p class="title font-weight-light">I'm sure you could win with a design that I&rsquo;d cast off as trash. Such is the curious case of the annual Garbage&nbsp;Festival.</p>
            <p class="micro uppercase"><a class="customHover customHover-3 customHover-lineSilver customHover-amber margin-top-1 ae-4 fromCenter" href="/ce-que-nous-faisons.html">Parcourir nos services</a></p>
          </div>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>
