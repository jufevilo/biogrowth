<template>
  <div class="">
    <div class="d-none d-md-flex">
      <v-img :src="require(`~/assets/images/main-image.png`)" />
    </div>
    <div class="d-md-none">
      <v-img :src="require(`~/assets/images/main-image-cut.png`)" />
      <div md="6" class="d-flex align-center background">
        <p class="ma-md-16 white--text pa-5">
          <span class="font-weight-bold">
            <v-icon color="white">mdi-star</v-icon> ESTABLISH AND INVEST</span
          >
          in a Business District Beautification Program to
          <strong> Bring Back Verona’s Downtown. </strong> <br /><br />
          <span class="font-weight-bold">
            <v-icon color="white">mdi-star</v-icon> ENSURE</span
          >
          responsible commercial and residential development in Verona by
          strengthening its zoning laws and empowering code enforcement.
          <br /><br />
          <span class="font-weight-bold">
            <v-icon color="white">mdi-star</v-icon> ENCOURAGE</span
          >
          home improvements by suspending new Township tax assessments for 2
          years.
          <br /><br />
          <span class="font-weight-bold">
            <v-icon color="white">mdi-star</v-icon> DEVELOP AND IMPLEMENT</span
          >
          the #LiVerona advertising campaign.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style></style>
