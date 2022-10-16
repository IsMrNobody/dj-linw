<template>
  <div>
    <v-img width="100%" src="/bg-banner.png">
      <div class="pos mt-5">
        <h1 class="d-none d-sm-flex">Anubis Productions</h1>
        <p class="d-none d-sm-flex">Night productions and events</p>
        <v-btn color="red" outlined class="d-none d-sm-flex">See more</v-btn>
      </div>
        <!-- <span>Live the experience of incredible nights with the best mixes of DJ Linw</span> -->
    </v-img>
    <v-row class="black pa-5 pt-10">
      <v-col>
        <h1 class="d-flex d-sm-none">Anubis Productions</h1>
        <p class="d-flex d-sm-none">Night productions and events</p>
      </v-col>
      <v-col cols>
        <v-btn color="red" outlined class="d-flex d-sm-none">Break Now</v-btn>
      </v-col>
    </v-row>
    <v-row>
      <v-col sm="8" cols>
        <iframe
          width="100%"
          height="400"
          src="https://www.youtube.com/embed/ykXgJB66AWA?controls=0"
          title="Breaking the rule"
          frameborder="0"
          allowfullscreen
        >
        </iframe>
      </v-col>
      <v-col cols class="pa-10">
        <v-card class="transparent" flat>
          <h1>Breaking the rules</h1>
          <p class="pa">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Autem sunt facilis labore est recusandae laudantium fugit commodi cumque quibusdam molestias! Vel ex autem nemo molestiae nesciunt qui saepe illo unde.</p>
        </v-card>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.pos {
  position: absolute;
  right: 40px;
}
.pa {
  text-decoration: none;
  text-transform: capitalize;
}
</style>