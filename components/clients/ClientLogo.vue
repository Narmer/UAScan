<template>
  <ul id="clients-list">
    <li v-for="logo in logos" :key="logo.src" class="text-left">
      <img
        class="ClientLogo"
        :alt="logo.alt"
        :src="logo.src"
      >
    </li>
  </ul>
</template>

<script>
module.exports = {
  data: function () {
    return {
      logos: [
      { alt: "Logo BBC", src: "/vuetify-logo.svg" },
      { alt: "test", src: "/vuetify-logo.svg" },
      { alt: "Logo BBC", src: "/vuetify-logo.svg" },
      { alt: "Logo BBC", src: "/vuetify-logo.svg" },
      { alt: "Logo BBC", src: "/vuetify-logo.svg" },
      { alt: "Logo BBC", src: "/vuetify-logo.svg" },
      { alt: "essais", src: "/vuetify-logo.svg" },
      { alt: "Logo BBC", src: "/vuetify-logo.svg" },
      { alt: "Logo BBC", src: "/vuetify-logo.svg" },
      { alt: "Logo BBC", src: "/vuetify-logo.svg" },
      { alt: "Logo BBC", src: "/vuetify-logo.svg" },
      { alt: "Logo BBC", src: "/vuetify-logo.svg" },
      { alt: "Logo BBC", src: "/vuetify-logo.svg" },
      { alt: "Logo BBC", src: "/vuetify-logo.svg" },
      { alt: "Logo BBC", src: "/vuetify-logo.svg" },
      { alt: "Logo BBC", src: "/vuetify-logo.svg" },
      { alt: "Logo BBC", src: "/vuetify-logo.svg" }
      ]
    }
  }
}
</script>

<style>
  ul {
    column-count: 6;
    list-style: none;
  }
  .ClientLogo {
    height: 100px;
    width: 145px;
  }
</style>

