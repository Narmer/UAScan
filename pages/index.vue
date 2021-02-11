<template>
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
