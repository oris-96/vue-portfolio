<template>
  <div id="app">
    <Navbar />
    <Hompage />
    <AboutMe />
    <Projects />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Hompage from "./components/Hompage.vue";
import AboutMe from "./components/AboutMe.vue";
import Projects from "./components/Projects.vue";

export default {
  name: "App",
  components: {
    Navbar,
    Hompage,
    AboutMe,
    Projects
  },
  data: () => {
    return {};
  }
};
</script>

<style lang="scss">
body {
  margin: 0;
}

#app {
  font-family: "Fondamento", cursive;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  position: relative;
  min-height: 100vh;
  background-image: linear-gradient(to right top, #485563, #29323c);
}
</style>

/* .logo{ position:absolute; top: 2rem; left: 2rem; width: 80px; } .card-line{
display: flex; justify-content: center; align-content: center; } .btn-contact{
text-align: center; text-transform: uppercase; text-decoration: none; padding:
.8rem 1rem; display: inline-block; border-radius: 6rem; font-size: .7rem;
border: none; color: white; background-color:black; margin-bottom: 30px; } */
