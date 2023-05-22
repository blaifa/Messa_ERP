<template>
  <TopNavBar></TopNavBar>
  <LateralNavBar></LateralNavBar>
  <router-view class="router-view"></router-view>
</template>

<script>
import LateralNavBar from "./components/LateralNavBar.vue";
import TopNavBar from "./components/TopNavBar.vue";
export default {
  name: "App",
  components: { LateralNavBar, TopNavBar },
};
</script>

<style>
#app {
  font-family: "Varela Round", sans-serif;
}
.router-view {
  margin-top: 6%;
  margin-left: 11%;
  overflow: auto;
}
</style>
