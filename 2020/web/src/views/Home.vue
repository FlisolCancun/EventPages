<template>
  <div class="home">
    <banner></banner>
    <about></about>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Banner from '@/components/Banner.vue'
import About from '@/components/About.vue'

export default {
  name: "home", 
  components: {
    Banner,
    About
  }
};
</script>
