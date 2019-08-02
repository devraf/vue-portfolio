<template>
  <div id="app">
    <Hero />
    <Footer />
  </div>
</template>

<script>
import Hero from "./components/Hero.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "app",
  components: {
    Hero,
    Footer
  }
};
</script>

<style>
@import url("https://use.typekit.net/vot4lml.css");

*,
*::after,
*::before {
  margin: 0;
  padding: 0;
  box-sizing: inherit;
}
html {
  font-size: 62.5%;
}
body {
  font-family: program, sans-serif;
  font-weight: 400;
  font-style: normal;

  font-size: 1.2rem;
  line-height: 1.7;
  color: hsla(0, 0%, 1%, 1);
  box-sizing: border-box;
  height: 100vh;
  animation: fadeIn 3s;
}
@keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
/* .component-fade-enter-active,
.component-fade-leave-active {
  transition: opacity 0.5s ease;
}
.component-fade-enter, .component-fade-leave-to {
  opacity: 0;
} */
</style>
