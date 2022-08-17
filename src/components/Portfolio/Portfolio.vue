<template>
  <section class="portfolio section" id="portfolio">
    <h2 class="section__title">Portfolio</h2>
    <span class="section__subtitle"> Most recent work </span>
    <div class="portfolio__container container swiper-container">
      <div class="swiper-wrapper">
        <Swiper :portfolio="flask_mngr"></Swiper>
        <Swiper :portfolio="debt_mngr"></Swiper>
      </div>
    </div>
  </section>
</template>


<script>
import Swiper from "./Swiper";
export default {
  name: "Portfolio",
  components: {
    Swiper,
  },
  data() {
    return {
     
      flask_mngr: {
        portfolio__title: "Fire Flask Manager",
        portfolio__description:
          "A web App for managing fire flasks and their owners. The app focuses on notifying the user of flask expirecy date. I used Vue.js & Larave + MySQL in this project.",
        portfolio__img: "flask_mngr.png",
        portfolio__url: "#",
      },
      debt_mngr: {
        portfolio__title: "Debt Manager",
        portfolio__description:
          "A web App for debts managment. It's just a test app, built with Vue.js & Firebase.",
        portfolio__img: "debt_mngr.png",
        portfolio__url: "https://debt-manager.netlify.app/",
      },
    };
  },
  methods: {},
};
</script>
