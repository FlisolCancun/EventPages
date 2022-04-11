<template>
  <section>
    <div class="hero-banner">
      <div class="hero-banner__intro">
        <Title content="Flisol Cancún 2022" />
        <p class="hero-banner__copy">
          El festival latinoamericano de instalación de software libre “FLISOL”
          es el evento de difusión orientado a la filosofía del software libre
          más grande de Latinoamérica. Está dirigido a todo tipo de personas
          estudiantes, profesores, ingenieros, entusiastas y público en general.
        </p>
        <ul class="hero-banner__extrainfo">
          <li class="font-extra">30 de Abril</li>
          <li class="font-extra">12:00 PM GTM-5</li>
        </ul>
      </div>
      <div class="hero-banner__cover">
        <img src="../assets/clumsy.svg" alt="clumsy" />
      </div>
    </div>
  </section>
</template>

<script>
import Title from "./Title.vue";
export default {
  components: { Title },
};
</script>
