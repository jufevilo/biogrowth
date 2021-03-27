<template>
  <div>
    <v-card
      min-height="100px"
      flat
      tile
      color="#00143F"
      class="d-flex justify-center white--text"
    >
      <v-card-title class="px-md-16 text-center container">
        <p class="d-none d-md-flex headline my-0">
          Michael has audacious goals for Verona, ideas that will: benefit
          residents now and for years to come; encourage small businesses to
          stay and flourish; and promote downtown’s recovery and bring shoppers
          back to town
        </p>
        <p class="d-md-none my-0">
          Michael has audacious goals for Verona, ideas that will: benefit
          residents now and for years to come; encourage small businesses to
          stay and flourish; and promote downtown’s recovery and bring shoppers
          back to town
        </p>
      </v-card-title>
    </v-card>
    <div class="py-16">
      <v-row class="ma-0">
        <v-col md="6" sm="12" class="d-flex align-center">
          <p class="ma-md-10 headline pa-5">
            <v-icon color="red">mdi-star</v-icon>
            A Downtown Beautification Program to Bring Back Verona’s Downtown.
            We will beautify downtown and bring functional and creative projects
            to Verona, such as murals by local artists; decorative seasonal
            lamppost banners; tree grates to keep weeds out and the sidewalks
            looking clean and beautiful; aesthetically-pleasing, cloth holiday
            meter covers; Big Belly garbage cans; and interactive, functional
            art installations to bring people to town and keep them shopping and
            eating locally downtown.
            <br /><br />
            <v-icon color="red">mdi-star</v-icon> Responsible, reduced and
            sustainable building development in Verona <br /><br />
            <v-icon color="red">mdi-star</v-icon>
            Encouragement to homeowners to stay in town and do home improvements
            by suspending new township assessment for 2 years thereby increasing
            property values and bringing business to local small businesses,
            such as contractors, painters, siders, electricians, flooring
            installers, plumbers, etc. to enrich the local economy and small
            business owners in town and surrounding areas.
            <br /><br />
            <v-icon color="red">mdi-star</v-icon> A fully coordinated and
            cooperative township and Board of Ed through expansion of sports,
            recreation and school programming to improve quality of life for all
            residents. <br /><br />
          </p>
        </v-col>
        <v-col md="6" sm="12" class="d-flex align-center flex-column">
          <v-img
            :src="require(`~/assets/images/second-image.png`)"
            max-height="600px"
            class="mt-md-16"
          />
        </v-col>
      </v-row>
      <div class="d-none d-md-flex">
        <v-img :src="require(`~/assets/images/verona.png`)" />
      </div>
      <div class="d-md-none">
        <v-img :src="require(`~/assets/images/verona-cut.png`)" />
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style></style>
