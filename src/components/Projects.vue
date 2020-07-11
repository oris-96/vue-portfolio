<template>
  <div id="project" class="project-container">
    <h1 class="project-heading">Projects</h1>
    <div class="project-list">
      <div class="project-card">
        <h2>Book finder app</h2>
        <hr />
        <p>built with vuejs,html, css,axios,bootstrap</p>
        <hr />
        <div class="project-links">
          <a href="#">
            <i class="fas fa-external-link-alt fa-2x"></i>
          </a>
          <br />
          <a href="#">
            <i class="fa fa-github fa-2x" aria-hidden="true"></i>
          </a>
        </div>
      </div>
      <div class="project-card">
        <h2>IOT mailbox</h2>
        <hr />
        <p>Built with python, node, express,js</p>
        <hr />
        <div class="project-links">
          <a href="#">
            <i class="fas fa-external-link-alt fa-2x"></i>
          </a>
          <br />
          <a href="#">
            <i class="fa fa-github fa-2x" aria-hidden="true"></i>
          </a>
        </div>
      </div>
      <div class="project-card">
        <h2>project title</h2>
        <hr />
        <p>brief details</p>
        <hr />
        <div class="project-links">
          <a href="#">
            <i class="fas fa-external-link-alt fa-2x"></i>
          </a>
          <br />
          <a href="#">
            <i class="fa fa-github fa-2x" aria-hidden="true"></i>
          </a>
        </div>
      </div>
      <div class="project-card">
        <h2>project title</h2>
        <hr />
        <p>brief details</p>
        <hr />
        <div class="project-links">
          <a href="#">
            <i class="fas fa-external-link-alt fa-2x"></i>
          </a>
          <br />
          <a href="#">
            <i class="fa fa-github fa-2x" aria-hidden="true"></i>
          </a>
        </div>
      </div>
      <div class="project-card">
        <h2>project title</h2>
        <hr />
        <p>brief details</p>
        <hr />
        <div class="project-links">
          <a href="#">
            <i class="fas fa-external-link-alt fa-2x"></i>
          </a>
          <br />
          <a href="#">
            <i class="fa fa-github fa-2x" aria-hidden="true"></i>
          </a>
        </div>
      </div>
      <div class="project-card">
        <h2>project title</h2>
        <hr />
        <p>brief details</p>
        <hr />
        <div class="project-links">
          <a href="#">
            <i class="fas fa-external-link-alt fa-2x"></i>
          </a>
          <br />
          <a href="#">
            <i class="fa fa-github fa-2x" aria-hidden="true"></i>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.project {
  &-container {
    min-height: 100vh;
    display: block;
    margin-top: 100px;
    margin-left: 200px;
    padding: 30px;
  }
  &-heading {
    display: flex;
    align-items: center;
    color: #e4e3e3;
    position: relative;

    &::after {
      content: "";
      height: 1px;
      display: block;
      background-color: #e4e3e3;
      width: 400px;
      margin-left: 15px;
    }
  }
  &-list {
    display: grid;
    grid-template-columns: minmax(140px, 250px) minmax(140px, 250px) minmax(
        140px,
        250px
      );
    margin: 40px;
  }

  &-card {
    max-height: 100%;
    width: 90%;
    border: 1px solid rgba($color: #000000, $alpha: 0.2);
    border-radius: 5px;
    box-shadow: 1px 3px rgba($color: #000000, $alpha: 0.2);
    display: block;
    text-align: center;
    color: #e4e3e3;
    padding: 30px;
    margin: 30px;
  }

  &-links {
    display: flex;
    justify-content: space-around;
    align-items: center;
    margin-top: 40px;
  }
}
</style>