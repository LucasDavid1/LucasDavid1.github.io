<template>
    <nav>
      <ul>
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/projects">Projects</router-link></li>
      </ul>
    </nav>
  </template>
  
  <script>
  export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name: 'Navbar',
  };
  </script>
  
  <style scoped>
  nav {
    background-color: #333;
    padding: 1rem;
  }
  ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
  }
  li {
    margin-right: 1rem;
  }
  a {
    color: #fff;
    text-decoration: none;
  }
  a.active {
    text-decoration: underline;
  }
  </style>
  