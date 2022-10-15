<template>
  <v-row>
    <v-card width="100vw" class="black">
      <div class="liston d-none d-lg-flex d-xl-none"></div>
      <v-col class="simbol">
        <v-img class="mx-auto sym" src="/logo-png-1.png"></v-img>
        <v-icon class="ml-5 mt-4 social">mdi-facebook</v-icon>
        <v-icon class="ml-5 mt-4 social">mdi-instagram</v-icon>
        <v-icon class="ml-5 mt-4 social">mdi-whatsapp</v-icon>
      </v-col>
      <v-card class="transparent">
        <!-- <v-col class="pa-4">
          <v-img max-width="300" class="mx-auto" src="/logo-png-0.png"></v-img>
        </v-col> -->
        <div class="title">
          <h1>
            ACID DJ
          </h1>
          <div>
            <p class="pa">Custom shows for your party night</p>
          </div>
          <span></span>
        </div>
        <v-img class="perfil" src="/perfil.png"></v-img>
      </v-card>
    </v-card>
  </v-row>
</template>

<script>
export default {}
</script>

<style>
.perfil {
  height: 100vh;
  opacity: 0.2;
}
.title {
  margin-top: 520px;
  margin-left: 45px;
  position: absolute;
  font-weight: bold;
  transition: 1s;
}
h1 {
  font-weight: 900;
  font-family: "Helvetica", serif;
}
p {
  text-decoration: underline;
  text-decoration-color: red;
  font-size: 1em;
  text-transform: uppercase;
}
.simbol {
  position: absolute;
  right: 40px;
  margin-top: 250px;
  z-index: 200;
  max-width: 90px;
}
.social {
  transform: scale(1);
  transition: width 1.5s;
}
.social:hover {
  transform: scale(2);
  color: red;
}
.liston {
  width: 30px;
  height: 100%;
  position: absolute;
  z-index: 40;
  top: -100px;
  right: 300px;
  background-color: red;
}
.sym {
  rotate: 0deg;
  transition: 1s;
}
.sym:hover {
  rotate: 360deg;
}
</style>