<template>
  <div>
      <v-row style="" no-gutters> 
          <v-col  cols="12" xl="9" lg="9" class="red bg2 " style="padding:5%">
              <p class="font-14">Fruit combination <br> for daily juice</p>
              <p><v-avatar class="mt-n1" size="24" color=""><v-img eager src="https://images.unsplash.com/photo-1535295972055-1c762f4483e5?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=80"></v-img></v-avatar> <span class="weight-600 font-4 mb-n1">Samantha William</span></p>
              <v-row>
                  <v-col cols="7" xl="4" lg="4">
                      <p class="font-4">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna</p>
                  </v-col>
              </v-row>
          </v-col>
           <v-col cols="12" xl="3" lg="3" style="padding:2%;padding-top:5%" class="">
               <p class="weight-600 font-11">Top Contributors</p>

               <br>

              <v-row no-gutters>
                  <v-col v-for="i in 6" :key="i" cols="6" xl="12" lg="12">
                       <div  class="mb-7">
                   <v-row align="center"  justify="center" no-gutters>
                       <v-avatar size="45"><v-img eager src="https://images.unsplash.com/photo-1535295972055-1c762f4483e5?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=80"></v-img></v-avatar>
                       <div class="ml-3">
                           <p class="font-15 weight-600 mb-n1">Andrea Wise</p>
                           <p class="font-4 grey--text mb-n1">135 articles</p>
                       </div>
                       <v-spacer></v-spacer>
                   </v-row>
               </div>
                  </v-col>
              </v-row>
           </v-col>
      </v-row>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.bg2{
    background: url('../../assets/bg2.png');
    background-size: cover;
}
</style>