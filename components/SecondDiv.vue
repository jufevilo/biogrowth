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
        <p class="d-none d-md-flex display-1 my-0">
          Biogrowth transforma miradas
        </p>
        <p class="d-md-none title my-0">Biogrowth transforma miradas</p>
      </v-card-title>
    </v-card>
    <div>
      <div class="text-center">
        <h2 class="display-2 font-weight-bold my-10 color-title">
          Componentes:
        </h2>
      </div>
      <div class="pa-16 d-flex flex-wrap justify-center">
        <v-img
          :src="require(`~/assets/images/componentes/1.jpeg`)"
          max-width="280"
          max-height="500"
          class="ma-2"
        />
        <v-img
          :src="require(`~/assets/images/componentes/2.jpeg`)"
          max-width="280"
          max-height="500"
          class="ma-2"
        />
        <v-img
          :src="require(`~/assets/images/componentes/3.jpeg`)"
          max-width="280"
          max-height="500"
          class="ma-2"
        />
        <v-img
          :src="require(`~/assets/images/componentes/4.jpeg`)"
          max-width="280"
          max-height="500"
          class="ma-2"
        />
        <v-img
          :src="require(`~/assets/images/componentes/5.jpeg`)"
          max-width="280"
          max-height="500"
          class="ma-2"
        />
        <v-img
          :src="require(`~/assets/images/componentes/6.jpeg`)"
          max-width="280"
          max-height="500"
          class="ma-2"
        />
      </div>
    </div>
    <div>
      <div class="text-center">
        <h2 class="display-2 font-weight-bold my-10 color-title">
          Modo de uso:
        </h2>
      </div>
      <div class="pa-16 d-flex flex-wrap justify-center">
        <v-img
          :src="require(`~/assets/images/uso/1.jpeg`)"
          class="ma-2"
          max-width="280"
          max-height="500"
        />
        <v-img
          :src="require(`~/assets/images/uso/2.jpeg`)"
          class="ma-2"
          max-width="280"
          max-height="500"
        />
        <v-img
          :src="require(`~/assets/images/uso/3.jpeg`)"
          class="ma-2"
          max-width="280"
          max-height="500"
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style></style>
