<template>
  <div>
    <div class="bg">
      <div class="filt">
        <v-container>
        <v-row align="end" justify="center" style="height:100vh">
          <v-col class="d-none d-sm-flex" cols="12" xl="6" lg="6" />
          <v-col cols="12" xl="6" lg="6"> 
            <div style="" class=" cont pa-2">
                <v-row style="height:100%;" align="center" justify="center" no-gutters>
                  <v-chip style="border-radius:0px;color:#4E9AA9"  class="font-4 weight-600" color="white"> NEW RECIPE</v-chip>
                  <v-spacer></v-spacer>
                  <p class="mb-n1 weight-600 font-4">Delicious fruit juice combinations</p>
                  <v-spacer></v-spacer>
                  <v-btn class="mb-n1" small icon plain><v-icon color="#4E9AA9">mdi-arrow-right</v-icon></v-btn>
                </v-row>
            </div>
            <p class="font-1 weight-600 hero-color" style="line-height:1.2">Simple and Tasty Juice Recipes</p>
            <p class="font-2 hero-color" style="margin-right:20%">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            
          </v-col>
        </v-row>
      </v-container>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Hero",

  components: {},
};
</script>
<style>
.bg {
  background: url("../../assets/hero1.png") ;
  background-size: cover;
  height: 100vh;
}
.cont{
  height:7vh !important;
  width:70%;
  background:#D9E7ED;
  color: #4E9AA9 !important;
}
.hero-color{
  color: black;
}
@media screen and (max-width:650px) {
  .bg {
  background: url("../../assets/hero1.png") ;
  background-size: cover;
  height: 100vh;
 

}
  .hero-color{
  color: white ;
}
.cont{
  height:7vh !important;
  width:90%;
  background:#D9E7ED;
  color: #4E9AA9 !important;
}
.filt{
  backdrop-filter:  contrast(50%);
}
}
</style>
