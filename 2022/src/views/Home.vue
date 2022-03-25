<template>
  <div class="home">
    <div class="l-section">
      <banner></banner>
    </div>
    <div class="l-section">
      <about></about>
    </div>
    <div class="l-section">
      <schedule></schedule>
    </div>
    <div class="l-section">
      <footer></footer>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

import Banner from "@/components/Banner.vue";
import About from "@/components/About.vue";
import Schedule from "@/components/Schedule.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "Home",
  components: {
    Banner,
    About,
    Schedule,
    Footer,
  },
};
</script>
<style>
body {
  font-family: resist, sans-serif;
  overflow: hidden;
}

.l-section {
  width: 100vw;
  height: 100vh;
}

@media screen and (min-width: 1024px) {
  .works__title {
    font-size: 5rem;
  }
}
.works__title {
  margin: 0;
  font-size: 5rem;
  font-weight: bold;
  line-height: 1.75;
}
</style>
