<template>
  <section class="about section" id="about">
    <h2 class="section__title">About Me</h2>
    <span class="section__subtitle"> My introduction </span>
    <div class="about__container container grid">
      <img src="~@/assets/img/noufel.png" alt="" class="about__img" />
      <div class="about__data">
        <p class="about__description">
          My name's <strong>Noufle MED Hadi Lalmi</strong>. I am a
          <strong>Full-Stack developer</strong> with <strong>+2 years</strong> of
          experience. I mainly
          use <strong>Vue js</strong> to realize my web projects as well as some
          knowledge in <strong>Laravel</strong> for the BackEnd. Also I have basic knowledge
          in <strong>Artificial Intelligence</strong>. I like to make
          fun and interactive things with code because in the end, there are
          three possible reactions to any design: yes, no and
          <strong>WAHOU!</strong>, the third one is the one I'm aiming for.
        </p>
        <div class="about__info">
          <div>
            <span class="about__info-title">+2</span>
            <span class="about__info-name"
              >Years <br />
              experience</span
            >
          </div>
          <div>
            <span class="about__info-title">+3</span>
            <span class="about__info-name"
              >Completed <br />
              project</span
            >
          </div>
          <div>
            <span class="about__info-title">2</span>
            <span class="about__info-name"
              >Companies <br />
              worked</span
            >
          </div>
        </div>
        <div class="about__buttons">
          <a
            href="#"
            class="button button--flex"
            target="_blank"
          >
            Download CV<i class="fas fa-download button__icon"></i>
          </a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "About",
  components: {},
  data() {
    return {};
  },
};
</script>