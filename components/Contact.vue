<template>
  <div>
    <v-card
      min-height="100px"
      flat
      tile
      color="#647547"
      class="d-flex justify-center white--text"
    >
      <v-card-title>
        <p class="d-none d-md-flex display-1 my-0">Testimonios</p>
        <p class="d-md-none title my-0">Testimonios</p>
      </v-card-title>
    </v-card>
    <div class="pt-16 d-flex justify-center">
      <p>
        Biogrowth, através del tiempo se a enfocado en la efectividad, día a día
        trabajamos para delvolverle la mirada y la confianza a cientos de
        mujeres.
      </p>
    </div>
    <v-card elevation="2" max-width="444" height="780" class="mx-auto"
      ><v-carousel height="780" hide-delimiters>
        <v-carousel-item>
          <v-img :src="require(`~/assets/images/carousel/1.jpeg`)"
        /></v-carousel-item>
        <v-carousel-item>
          <v-img :src="require(`~/assets/images/carousel/2.jpeg`)"
        /></v-carousel-item>
        <v-carousel-item>
          <v-img :src="require(`~/assets/images/carousel/3.jpeg`)"
        /></v-carousel-item>
        <v-carousel-item>
          <v-img :src="require(`~/assets/images/carousel/4.jpeg`)"
        /></v-carousel-item>
        <v-carousel-item>
          <v-img :src="require(`~/assets/images/carousel/5.jpeg`)"
        /></v-carousel-item>
        <v-carousel-item>
          <v-img :src="require(`~/assets/images/carousel/6.jpeg`)"
        /></v-carousel-item>
        <v-carousel-item>
          <v-img :src="require(`~/assets/images/carousel/7.jpeg`)"
        /></v-carousel-item>
        <v-carousel-item>
          <v-img :src="require(`~/assets/images/carousel/8.jpeg`)"
        /></v-carousel-item> </v-carousel></v-card
    >>
  </div>
</template>
<script>
export default {
  data() {
    return {}
  },
}
</script>
<style></style>
