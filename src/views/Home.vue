<template>
  <span>
  	<home-hero></home-hero>
  	<home-details></home-details>
  	<home-plans></home-plans>
  </span>
</template>

<script>
// @ is an alias to /src
import HomeHero from '@/components/HomeHero.vue';
import HomeDetails from '@/components/HomeDetails.vue';
import HomePlans from '@/components/HomePlans.vue';

export default {
  name: 'home',
  components: {
    HomeHero,
    HomeDetails,
    HomePlans,
  },
};
</script>
