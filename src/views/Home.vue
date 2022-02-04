<template>
  <div>
   <heroHomeVue />
   <latestHomeVue />
   <popularHomeVue />
   <contribHomeVue />
   <trendingHomeVue />
  </div>
</template>

<script>
import contribHomeVue from '../components/home/contrib.home.vue';
import heroHomeVue from '../components/home/hero.home.vue';
import latestHomeVue from '../components/home/latest.home.vue';
import popularHomeVue from '../components/home/popular.home.vue';
import trendingHomeVue from '../components/home/trending.home.vue';

export default {
  name: "Home",

  components: {
    heroHomeVue,
    latestHomeVue,
    popularHomeVue,
    contribHomeVue,
    trendingHomeVue
  },
};
</script>
<style>


</style>
