<template>
  <fragment>
    <navbar></navbar>
    <main>
      <banner></banner>
      <schedule></schedule>
      <sponsors></sponsors>
    </main>
  </fragment>
</template>

<script>
import Navbar from "@/components/Navbar";
import Banner from "@/components/Banner";
import Sponsors from "@/components/About";
import Schedule from "@/components/Schedule";
import Footer from "@/components/Footer";

export default {
  name: "Home",
  components: {
    Navbar,
    Banner,
    Sponsors,
    Schedule,
    Footer,
  },
};
</script>
