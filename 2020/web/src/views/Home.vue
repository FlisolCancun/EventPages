<template>
  <div class="home">
    <banner></banner>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Banner from '@/components/Banner.vue'

export default {
  name: "home", 
  components: {
    Banner
  }
};
</script>
