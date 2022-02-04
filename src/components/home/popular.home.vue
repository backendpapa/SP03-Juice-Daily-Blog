<template>
  <div>
    <v-container>
      <v-row no-gutters>
        <v-col cols="12" lg="4" xl="4">
          <p class="font-11 weight-600">Popular</p>
          <v-row no-gutters>
            <v-col class="" cols="12">
              <v-card class="mb-3 card"  flat>
                <v-row class="" align="center" justify="center" no-gutters>
                    <v-col cols="10">
                         <p class="font-13 mb-n1" style="margin-right: 15%">
                    Fruit juices to boost your immune
                  </p>
                    </v-col>
                 
                    <v-col cols="2">
                         <v-btn icon small><v-icon>mdi-arrow-right</v-icon></v-btn>
                    </v-col>
                </v-row>
              </v-card>
              <v-card class="mb-3 card"  flat>
                <v-row class="" align="center" justify="center" no-gutters>
                    <v-col cols="10">
                         <p class="font-13 mb-n1" style="margin-right: 15%">
                    Juice variations using avocado
                  </p>
                    </v-col>
                 
                    <v-col cols="2">
                         <v-btn icon small><v-icon>mdi-arrow-right</v-icon></v-btn>
                    </v-col>
                </v-row>
              </v-card>
              <v-card class="mb-3 card"  flat>
                <v-row class="" align="center" justify="center" no-gutters>
                    <v-col cols="10">
                         <p class="font-13 mb-n1" style="margin-right: 15%">
                    Simple recipe strawberry juice
                  </p>
                    </v-col>
                 
                    <v-col cols="2">
                         <v-btn icon small><v-icon>mdi-arrow-right</v-icon></v-btn>
                    </v-col>
                </v-row>
              </v-card>
            </v-col>
          </v-row>
        </v-col>

        <v-col cols="12" xl="4" lg="4">
          <div class="">
            <v-img eager  height="200" src="../../assets/food4.png"></v-img>
            <div style="margin-top:4%">
                <p class="font-4">
              <span class="" style="color:#11BCC7">FRUIT</span>
              <span class="grey--text">- 5mins read</span>
            </p>
            <p class="font-11 weight-600">Simple Juice Recipes to boost your immune system</p>
            <p class="font-3">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
            
            </div>
          </div>
        </v-col>
        <v-col cols="12" xl="4" lg="4">

          <iframe  width="100%" height="100%"  src="https://www.youtube.com/embed/YY_zr8ELP_w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen autoplay="1"></iframe>
           
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
import 'video.js/dist/video-js.css'
export default {
    data() {
      return {
        // videojs options
       
      }
    },
    mounted() {
      // console.log('this is current player instance object', this.player)
     
    },
    
  }
</script>

<style>
.box{
    height: 10vh !important;
}
.card{
    height: 18vh;
}
@media screen and (max-width:600px) {
    .card{
    height: 10vh;
}   
}
</style>