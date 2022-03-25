<template>
  <section class="l-wrapper">
    <div class="about-container">
      <h2 class="works__title js-move-up">Acerca de</h2>
      <div class="about-container__content">
        <p class="works__description">
          El festival latinoamericano de instalación de software libre “FLISOL”
          es el evento de difusión orientado a la filosofía del software libre
          más grande de Latinoamérica. Está dirigido a todo tipo de personas
          estudiantes, profesores, ingenieros, entusiastas y público en general.
          El evento se realiza cada año desde 2005, adoptando el 4to sábado de
          abril de cada año para su festejo. El principal objetivo es promover
          el uso del software libre ilustrando a la audiencia su filosofía,
          alcance, desarrollo e impacto en diferentes aspectos de la sociedad.
          La entrada al evento es
          <strong class="color-accent">totalmente gratuita</strong> para todo el
          público. La organización del evento es llevada a cabo por medio de un
          grupo de entusiastas preocupados por promover el uso del software y de
          sus cuatro libertades basadas en la ética y el desarrollo de la
          sociedad para el conocimiento.
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style>
.about-container__content {
  display: grid;
  grid-template-columns: repeat(12, 1fr);
}
.works__description {
  margin: 0;
  font-size: 40px;
  line-height: 50px;
  letter-spacing: 0;
  grid-column: 2 / -3;
  padding: 1rem;
}
</style>
