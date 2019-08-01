<template>
  <section class="hero">
    <div>
      <p class="hero-text">{{ name }}</p>
      <svg width="303" height="9">
        <rect x="0" y="0" width="297" height="3" fill="hsla(0, 100%, 0%, 1)" />
      </svg>
      <p class="hero-text">{{ job }}</p>
    </div>
  </section>
</template>

<script>
export default {
  name: "Hero",
  data() {
    return {
      name: "Rafael Perales",
      job: "Front-End Developer"
    };
  }
};
</script>

<style>
.hero {
  display: grid;
  grid-template-columns: repeat(1, 1fr);
  height: 80vh;
}

.hero-text {
  text-align: center;
  font-size: 3.5rem;
}

.hero div {
  align-self: center;
  justify-self: center;
}

.hero svg {
  padding: 0.3rem;
}
</style>
