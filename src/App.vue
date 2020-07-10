<template>
  <div :style="[backgroundImage, color]" id="app">
    <Navbar />
    <Hompage />
    <AboutMe />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Hompage from "./components/Hompage.vue";
import AboutMe from "./components/AboutMe.vue";

export default {
  name: "App",
  components: {
    Navbar,
    Hompage,
    AboutMe
  },
  data: () => {
    return {
      backgroundImage: {
        backgroundImage: "linear-gradient(to right top, #485563, #29323c)"
      },
      color: {
        color: "#fff"
      }
    };
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
  text-align: center;
  position: relative;
  height: 100vh;
  background-repeat: repeat;
  background-size: cover;
  background-position: top;
  position: relative;
}
</style>

/* .logo{ position:absolute; top: 2rem; left: 2rem; width: 80px; } .card-line{
display: flex; justify-content: center; align-content: center; } .btn-contact{
text-align: center; text-transform: uppercase; text-decoration: none; padding:
.8rem 1rem; display: inline-block; border-radius: 6rem; font-size: .7rem;
border: none; color: white; background-color:black; margin-bottom: 30px; } */
