<template>
  <v-app>
    <div>
      <div>
        <v-img :src="require(`~/assets/images/header.png`)" />
      </div>
    </div>
    <div class="">
      <v-app-bar
        class="d-flex justify-md-center align-center appbar"
        :class="scroll ? 'appbar' : 'appbar2'"
      >
        <v-app-bar-nav-icon
          x-large
          class="d-flex d-md-none"
          @click.stop="drawer = !drawer"
        ></v-app-bar-nav-icon>
        <h5 class="text-h5 d-flex d-md-none">Transformando Miradas</h5>
        <div class="d-none d-md-flex">
          <v-btn text class="title text-capitalize" color="#647547" to="#home"
            >Home</v-btn
          >
          <v-btn text class="title text-capitalize" color="#647547" to="#donate"
            >Nosotros</v-btn
          >
          <v-btn
            text
            class="title text-capitalize"
            color="#647547"
            to="#contact"
            >Testimonios</v-btn
          >
          <v-btn
            text
            class="title text-capitalize"
            color="#647547"
            to="#how-to-vote"
            >Tienda</v-btn
          >
        </div>
      </v-app-bar>

      <v-navigation-drawer
        v-model="drawer"
        absolute
        temporary
        color="#647547"
        dark
      >
        <v-list nav dense>
          <v-list-item-group active-class="deep-purple--text text--accent-4">
            <v-list-item to="#home">
              <v-list-item-title> Home</v-list-item-title>
            </v-list-item>

            <v-list-item to="#donate">
              <v-list-item-title>Nosotros</v-list-item-title>
            </v-list-item>

            <v-list-item to="#contact">
              <v-list-item-title> Testimonios</v-list-item-title>
            </v-list-item>

            <v-list-item to="#how-to-vote">
              <v-list-item-title> Tienda </v-list-item-title>
            </v-list-item>
          </v-list-item-group>
        </v-list>
      </v-navigation-drawer>
    </div>
    <v-main>
      <nuxt />
    </v-main>
    <v-footer min-height="80px" class="d-flex justify-center" color="#647547">
      <v-btn
        text
        dark
        href="https://api.whatsapp.com/send?phone=+573506504225"
        target="_blank"
      >
        <v-icon class="mr-2">mdi-phone</v-icon>350 650 4225</v-btn
      >
      <v-btn
        href="https://goo.gl/maps/TQb3inRJ8drbBw4M8"
        text
        dark
        target="_blank"
      >
        <v-icon class="mr-2">mdi-map-marker</v-icon>Calle 40 #51-109
        Itagui</v-btn
      >
      <v-btn
        href="https://www.instagram.com/biogrowthoficial/?hl=en"
        target="_blank"
        text
        dark
      >
        <v-icon class="mr-2">mdi-instagram</v-icon>biogrowthoficial
      </v-btn>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  data: () => ({
    scroll: true,
    menu: '',
    drawer: false,
  }),
  mounted() {
    window.addEventListener('scroll', this.scrollFunction)
  },
  methods: {
    scrollFunction(event) {
      if (window.scrollY > 0) {
        this.scroll = false
      } else {
        this.scroll = true
      }
    },
  },
}
</script>
<style>
.appbar {
  position: fixed !important;
  z-index: 1;
  width: 100%;
}
.appbar2 {
  position: fixed !important;
  top: 0;
  z-index: 1;
  width: 100%;
}
</style>
