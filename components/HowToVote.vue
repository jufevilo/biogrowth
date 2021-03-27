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
        <p class="d-none d-md-flex display-1 my-0">Tienda</p>
        <p class="d-md-none title my-0">Tienda</p>
      </v-card-title>
    </v-card>
    <div class="py-16">
      <v-row class="pa-5 ma-0 d-flex justify-center align-center">
        <v-col md="6" class="d-flex justify-center pa-5">
          <v-img
            :src="require(`~/assets/images/product.jpg`)"
            max-height="500"
            max-width="500"
          />
        </v-col>
        <v-col md="6" class="pa-5 text-center">
          <p class="display-4 font-weight-bold color-title">¡Solo por hoy!</p>
          <p class="display-3 font-weight-bold color-title">
            20% de Descuento.
          </p>
          <v-btn
            href="https://biz.payulatam.com/L0e1facE54BC08C"
            color="green"
            x-large
            dark
            class="display-2"
            >$38.900 <v-icon large class="mx-2">mdi-cart</v-icon></v-btn
          >
          <p class="caption">Presione el boton para comprar</p>
        </v-col>
      </v-row>
    </div>
  </div>
</template>
<script>
export default {}
</script>
<style>
.color-title {
  color: #647547;
}
</style>
