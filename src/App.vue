<template>
  <div
    
    class="relative"
  >
    <global-navigation />
    <div class="bg-grey-lighter w-full h-full min-h-screen">
      <div class="">
        <router-view />
      </div>
      <!-- <holding-page></holding-page> -->
    </div>
  </div>
</template>

<script>
// import HoldingPage from './components/Globals/HoldingPage.vue';
import Navigation from "./components/Globals/Navigation.vue";
export default {
  components: {
    "global-navigation": Navigation,
    // 'holding-page' : HoldingPage,
  }
};
</script>

<style lang="scss">
</style>