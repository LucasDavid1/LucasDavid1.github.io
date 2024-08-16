<template>
  <div>
    <Navbar />
    <div class="projects">
      <h1>My Projects</h1>
      <p>Here are some of the projects I've worked on:</p>
      <!-- Add project details here -->
    </div>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue';

export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'Projects',
  components: {
    Navbar,
  },
};
</script>

<style scoped>
.projects {
  text-align: center;
  padding: 2rem;
}
</style>
