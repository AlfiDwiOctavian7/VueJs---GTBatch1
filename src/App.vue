
<template>
  <div id="app">
    <navbarComponent></navbarComponent>
    <breadComponent></breadComponent>
    <galleyComponent></galleyComponent>
    <SliderComponent></SliderComponent>
    <footerComponent></footerComponent>
    <copyrightCmp></copyrightCmp>

  </div>

</template>


<script>
import navbarComponent from "./components/navbarComponent.vue";
import breadComponent from "./components/breadcrumtComponent.vue";
import galleyComponent from "./components/galleyComponent.vue";
import SliderComponent from "./components/sliderComponent.vue";
import footerComponent from "./components/footerComponent.vue";
import copyrightCmp from "./components/copyrightComponent.vue";

export default {
  name: "App",
  components: {
    navbarComponent,
    breadComponent,
    galleyComponent,
    SliderComponent,
    footerComponent,
    copyrightCmp
  },
}
</script>

<style>

</style>