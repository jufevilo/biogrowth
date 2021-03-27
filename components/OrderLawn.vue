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
        <p class="d-none d-md-flex display-1 my-0">
          Order lawn signs or car magnets
        </p>
        <p class="d-md-none title my-0">Order lawn signs or car magnets</p>
      </v-card-title>
    </v-card>
    <div class="py-16">
      <v-row class="ma-0">
        <v-col md="6" class="pa-5 ma-0 d-flex justify-center align-center">
          <v-card class="pa-5" outlined tile width="90%">
            <form class="">
              <v-text-field outlined dense label="Name" required></v-text-field>
              <v-text-field
                outlined
                dense
                label="E-mail"
                required
              ></v-text-field>
              <v-text-field
                outlined
                dense
                label="Mailing Address"
                required
              ></v-text-field>
              <p>
                Comments or Questions (indicate quantities of signs and magnets)
              </p>
              <v-text-field outlined required></v-text-field>
              <v-btn color="#00143F" block dark type="submit">
                Send Request
              </v-btn>
            </form>
          </v-card>
        </v-col>
        <v-col md="6" class="ma-0 d-flex flex-wrap justify-center align-center">
          <div class="text-center mx-3">
            <v-img
              :src="require(`~/assets/images/nochimson-magnet.png`)"
              max-height="320"
              max-width="320"
            />
            <p>CAR MAGNET</p>
          </div>
          <div class="text-center mx-3">
            <v-img
              :src="require(`~/assets/images/Nochimson-Lawn-sign.png`)"
              max-height="230"
              max-width="320"
            />
            <p class="mt-5">LAWN SIGN</p>
          </div>
        </v-col>
      </v-row>
    </div>
  </div>
</template>
<script>
export default {}
</script>
<style></style>
