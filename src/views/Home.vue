<template>
  <div>
    <Navbar />
    <div class="home">
      <h1>Welcome to My Portfolio</h1>
      <p>Hi, I'm [Your Name], a software engineer. Explore my projects and learn more about what I do.</p>
    </div>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue';

export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'Home',
  components: {
    Navbar,
  },
};
</script>

<style scoped>
.home {
  text-align: center;
  padding: 2rem;
}
</style>
