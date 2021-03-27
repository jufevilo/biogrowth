<template>
  <div>
    <v-card
      min-height="100px"
      flat
      tile
      color="#00143F"
      class="d-flex justify-center white--text"
    >
      <v-card-title>
        <p class="d-none d-md-flex display-1 my-0">How To Vote</p>
        <p class="d-md-none title my-0">How To Vote</p>
      </v-card-title>
    </v-card>
    <div class="py-16">
      <v-row class="pa-5 ma-0">
        <v-col md="6" class="d-flex justify-center pa-5">
          <v-img
            :src="require(`~/assets/images/verona-cut.png`)"
            max-height="230"
            max-width="320"
          />
        </v-col>
        <v-col md="6" class="d-flex justify-center pa-5">
          <v-img
            :src="require(`~/assets/images/ticket.jpg`)"
            max-height="230"
            max-width="320"
          />
        </v-col>
      </v-row>
      <div
        class="d-flex justify-center title font-weight-bold pa-5 text-center"
      >
        <p>
          The Municipal Election is Tuesday, May 11, 2021. Polls open at 6:00am
          and close at 8:00pm
        </p>
      </div>
    </div>
  </div>
</template>
<script>
export default {}
</script>
<style></style>
