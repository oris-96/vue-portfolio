<template>
  <div>
    <b-navbar>
      <div class="logo">
        <img class="logo__img" src="../assets/ibrahim.png" alt="Ibrahim" />
      </div>

      <b-navbar-nav>
        <b-nav-item href="#">About</b-nav-item>
        <b-nav-item href="#">Project</b-nav-item>
      </b-navbar-nav>
    </b-navbar>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
};
</script>

<style lang="scss" scoped>
.navbar {
  background-image: linear-gradient(to right top, #485563, #29323c);
  display: flex;
  justify-content: flex-end;
  box-shadow: 1px 2px rgba(58, 40, 40, 0.2);
  padding: 20px;
}

.navbar-light .navbar-nav .nav-link {
  color: #fff;
}

.logo {
  justify-self: flex-start;
  position: absolute;
  top: 10px;
  left: 40px;
}

.logo__img {
  height: 60px;
  width: 60px;
  filter: contrast(180%);
}
</style>
