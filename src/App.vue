<template>
  <v-app>
    <v-app-bar
      fixed
      color="white"
       
      flat
    >
      <div class="d-flex align-center">
        <v-avatar size="27" color="#11BCC7" class="white--text font-weight-bold">J</v-avatar>
        <span class="font-weight-bold ml-2 mb-n1" style="color:#11BCC7">JUICEDAILY</span>
      </div>

      <v-spacer></v-spacer>

    <div class="d-none d-sm-flex">
      <div class="d-flex align-center">
         <v-btn text style="text-transform:none" class="font-weight-light">BROWSE</v-btn>
     <v-btn text style="text-transform:none" class="font-weight-light">TRENDING</v-btn>
     <v-btn text style="text-transform:none" class="font-weight-light">CONTRIBUTORS</v-btn>
     <v-btn text style="text-transform:none" class="font-weight-light">COMMUNITY</v-btn>
      </div>
    </div>
     <v-spacer></v-spacer>
     <v-avatar style="border-radius:0px;height:115%;width:60px;margin-right:-20px" color="#FF553C"><v-icon color="white">mdi-magnify</v-icon></v-avatar>
    </v-app-bar>

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>
import "./css/fonts.css"
export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
