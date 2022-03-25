<template>
  <section>
    <div class="l-dot js-dot-holder">
      <div
        class="l-dot__item js-dot"
        style="transform: translate3d(0px, 156.786px, 0px)"
      ></div>
    </div>
    <div class="l-section l-section--intro">
      <div class="l-wrapper">
        <div class="intro">
          <h1 class="intro__title js-intro-title">FLISOL Cancún 2020</h1>
          <div class="intro-blob js-intro-image">
            <span class="intro-blob__line"></span>
          </div>
          <div class="intro__position-box">
            <p class="intro__position"></p>
            <p class="intro__position">
              <span class="icon">☞</span>
              <span class="text">Sábado, 30 de Abril</span>
            </p>
            <p class="intro__position">
              <span class="icon">☞</span>
              <span class="text">12:00 PM GMT-5</span>
            </p>
            <p class="intro__position">
              <span class="icon">☞</span>
              <span class="text"><a href="">Call For papers</a></span>
            </p>
          </div>
          <div class="intro__info-box">
            <p class="intro__info">Sede por definir</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style>
@media screen and (min-width: 1239px) {
  .intro__title {
    cursor: pointer;
    transition: color 0.3s;
  }
  .l-wrapper {
    padding-right: 5rem;
    padding-left: 5rem;
  }
  .intro {
    max-width: 55vw;
  }
}
.l-dot {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  z-index: -1;
  width: 73.4375rem;
  overflow: hidden;
}
.l-dot__item {
  position: absolute;
  top: -21.7rem;
  right: -29.325rem;
  width: 73.4375rem;
  height: 73.4375rem;
  background: radial-gradient(
    50% 50% at 50% 50%,
    #fcec62 0,
    hsla(0, 0%, 100%, 0) 100%
  );
}
.intro__position {
  margin: 0;
  font-size: 2.25rem;
  line-height: 1.7;
}
.intro__position-box {
  margin-top: 4rem;
}
.intro__info-box {
  margin-top: 3.75rem;
}
.intro__info {
  margin: 0;
  font-size: 1.9rem;
  letter-spacing: 0.03333em;
  line-height: 1.6;
}
.intro__info {
  margin: 0;
  font-size: 1.9rem;
  letter-spacing: 0.03333em;
  line-height: 1.6;
}
.intro {
  position: relative;
}

.l-wrapper {
  position: relative;
  width: 100%;
  margin-right: auto;
  margin-left: auto;
  padding-right: 2.5rem;
  padding-left: 2.5rem;
}
.l-section--intro {
  margin-bottom: 7.5rem;
  padding-top: 3.25rem;
}
.l-section {
  position: relative;
  z-index: 2;
}
.intro__title {
  margin: 0;
  font-size: 7rem;
  font-weight: 500;
  line-height: 1.27273em;
  font-weight: bold;
}
</style>
