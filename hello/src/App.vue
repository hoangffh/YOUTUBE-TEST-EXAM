<template>
  <div id="app">
   <TheHeader></TheHeader>
   <TheSideBar></TheSideBar>
  </div>
</template>

<script>
import TheHeader from '../src/components/layout/TheHeader.vue'
import TheSideBar from "../src/components/layout/TheSideBar.vue"
// import TheContainer from "../src/components/layout/TheContainer.vue"
export default {
  name: 'App',
  components: {
    TheHeader,
    TheSideBar,
    // TheContainer
  }
}
</script>

<style>
@import url(./css/main.css);
</style>
