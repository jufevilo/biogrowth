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
        <p class="d-none d-md-flex display-1 my-0">Contact Michael</p>
        <p class="d-md-none title my-0">Contact Michael</p>
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
                label="Phone Number"
                required
              ></v-text-field>
              <v-text-field
                outlined
                dense
                label="E-mail"
                required
              ></v-text-field>
              <v-btn color="#00143F" dark type="submit"> submit </v-btn>
              <v-btn color="#BF1B2C" dark> clear </v-btn>
              <v-btn
                color="#0F8FF2"
                icon
                dark
                large
                href="https://www.facebook.com/michaelnochimson"
                target="_blank"
              >
                <v-icon large>mdi-facebook</v-icon>
              </v-btn>
            </form>
          </v-card>
        </v-col>
        <v-col md="6" class="ma-0 d-flex justify-center">
          <v-img :src="require(`~/assets/images/office.jpg`)" />
        </v-col>
      </v-row>
    </div>
  </div>
</template>
<script>
export default {}
</script>
<style></style>
