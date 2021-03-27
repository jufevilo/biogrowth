<template>
  <v-app>
    <div>
      <div>
        <v-img :src="require(`~/assets/images/header-2x.png`)" />
      </div>
    </div>
    <div class="">
      <v-app-bar
        color="#00143F"
        dark
        class="d-flex justify-md-center align-center appbar"
        :class="scroll ? 'appbar' : 'appbar2'"
      >
        <v-app-bar-nav-icon
          x-large
          class="d-flex d-md-none"
          @click.stop="drawer = !drawer"
        ></v-app-bar-nav-icon>
        <h5 class="text-h5">Michael Nochimson</h5>
        <div class="d-none d-md-flex">
          <v-btn text class="title text-capitalize" color="white" to="#home"
            >Home</v-btn
          >
          <v-btn text class="title text-capitalize" color="white" to="#donate"
            >Donate</v-btn
          >
          <v-btn
            text
            class="title text-capitalize"
            color="white"
            to="#how-to-vote"
            >How to vote</v-btn
          >
          <v-btn
            text
            class="title text-capitalize"
            color="white"
            to="#order-lawn"
            >Order Lawn Signs and magnets</v-btn
          >
          <v-btn text class="title text-capitalize" color="white" to="#contact"
            >Contact Michael</v-btn
          >
        </div>
      </v-app-bar>

      <v-navigation-drawer
        v-model="drawer"
        absolute
        temporary
        color="#00143F"
        dark
      >
        <v-list nav dense>
          <v-list-item-group active-class="deep-purple--text text--accent-4">
            <v-list-item to="#home">
              <v-list-item-title> Home</v-list-item-title>
            </v-list-item>

            <v-list-item to="#donate">
              <v-list-item-title>DONATE</v-list-item-title>
            </v-list-item>

            <v-list-item to="#how-to-vote">
              <v-list-item-title> HOW TO VOTE</v-list-item-title>
            </v-list-item>

            <v-list-item to="#oder-lawn">
              <v-list-item-title>
                ORDER LAWN SIGNS AND MAGNETS
              </v-list-item-title>
            </v-list-item>
            <v-list-item to="#contact">
              <v-list-item-title> CONTACT MICHAEL</v-list-item-title>
            </v-list-item>
          </v-list-item-group>
        </v-list>
      </v-navigation-drawer>
    </div>
    <v-main>
      <nuxt />
    </v-main>
    <v-footer min-height="80px" class="d-flex justify-center" color="#00143F">
      <p class="red--text font-italic my-0">CONNECT WITH MICHAEL:</p>
      <v-btn to="" text dark>
        <v-icon class="mr-2">mdi-link-variant</v-icon>www.nochimson.com</v-btn
      >
      <v-btn
        href="https://www.facebook.com/michaelnochimson"
        target="_blank"
        text
        dark
      >
        <v-icon class="mr-2">mdi-facebook</v-icon>MichaelNochimson</v-btn
      >
      <p class="white--text my-0">PAID FOR BY NOCHIMSON NOW</p>
    </v-footer>
    <!-- Donate one -->
    <donate-bar />
    <div class="letrero d-none d-md-flex" :class="scroll ? 'sign1' : 'sign2'">
      <v-img
        :src="require(`~/assets/images/letrero.png`)"
        max-height="300px"
        max-width="300px"
      />
      <neon />
    </div>
    <div class="letrero d-flex d-md-none" :class="scroll ? 'sign1' : 'sign2'">
      <v-img
        :src="require(`~/assets/images/letrero.png`)"
        max-height="120px"
        max-width="120px"
      />
      <neon />
    </div>
  </v-app>
</template>

<script>
import Neon from '@/components/Neon'
import DonateBar from '@/components/DonateBar'
export default {
  components: { DonateBar, Neon },
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

.sign1 {
  position: fixed;
  top: 1%;
  right: 1%;
  z-index: 1;
}

.sign2 {
  display: none !important;
}
</style>
