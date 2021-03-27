<template>
  <v-footer min-height="80px" class="donate d-flex flex-column justify-center">
    <div
      class="flex-wrap justify-center align-center d-none d-sm-none d-md-flex"
    >
      <p class="headline font-weight-bold my-0 mx-5">Together we can do it:</p>
      <v-btn
        to="#donate"
        color="#BF1B2C"
        dark
        rounded
        x-large
        class="headline font-weight-bold mx-2"
        >DONATE</v-btn
      >
    </div>
    <!-- Donate two -->
    <div min-height="120px" class="d-md-none text-center" color="white">
      <p class="headline font-weight-bold my-0">Together we can do it:</p>
      <div class="d-flex flex-wrap justify-center">
        <v-btn
          to="#donate"
          color="#BF1B2C"
          dark
          rounded
          class="font-weight-bold ma-1"
          >DONATE</v-btn
        >
      </div>
    </div>
  </v-footer>
</template>

<script>
export default {}
</script>

<style>
.donate {
  position: sticky !important;
  bottom: 0%;
  width: 100%;
  border-top: 6px solid #bf1b2c !important;
}
</style>
