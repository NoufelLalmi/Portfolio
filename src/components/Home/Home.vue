<template>
  <section class="home section" id="home">
    <div class="home__container container grid">
      <div class="home__content grid">
        <SocialButtons></SocialButtons>
        <Blob></Blob>
        <HomeData
          :home__description="home__description"
          :home__subtitle="home__subtitle"
          :home__title="home__title"
          :button__content="button__content"
        ></HomeData>
      </div>
      <HomeScroll></HomeScroll>
    </div>
  </section>
</template>

<script>
import SocialButtons from "./SocialButtons";
import Blob from "./Blob";
import HomeData from "./HomeData";
import HomeScroll from "./HomeScroll";
export default {
  name: "Home",
  components: {
    SocialButtons,
    Blob,
    HomeData,
    HomeScroll,
  },
  data() {
    return {
      home__description:
        "Welcome to my portfolio.",
      home__subtitle: "I'm a Full Stack Developer",
      home__title: "Hi, I'm Noufle M.H Lalmi",
      button__content: "Contact me",
    };
  },
};
</script>

<style>
</style>