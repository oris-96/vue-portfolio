<template>
  <div id="about" class="about-container">
    <div class="about-heading-container">
      <h2 class="about-heading">About Me</h2>
    </div>

    <div class="about-content-container">
      <div class="about-content">
        <p>
          i'm Ibrahim, a software Engineer with a passion for problem solving, i studied Electrical
          /Electronics Engineering during my undergraduate bachelor's, i was always fascinated by software and how they were put together
          the curiosity made me start the journey of teaching myself how to code whilst i was pursuing my bachelor's,
          currently i am pursuing a masters in computer science and quantitative methods and i totally love it.
        </p>
        <p>
          I enjoy building performant applications with clean and dynamic user interface and an efficient backend architecture,
          i strive to grow and improve myself daily , i solve problems that help save my clients money
        </p>
        <p>Here are some of the technologies i'm proficient in:</p>

        <ul class="about-tech-container">
          <li class="about-tech">Python</li>
          <li class="about-tech">Javascript/ES5/ES2015</li>
          <li class="about-tech">HTML5</li>
          <li class="about-tech">CSS</li>
          <li class="about-tech">VUEjs</li>
          <li class="about-tech">NODEjs</li>
          <li class="about-tech">EXPRESS</li>
          <li class="about-tech">MongoDB</li>
          <li class="about-tech">NPM</li>
          <li class="about-tech">GIT</li>
          <li class="about-tech">SASS/SCSS</li>
          <li class="about-tech">Hyper</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.about {
  &-container {
    min-height: 100vh;
    display: block;
    margin-top: 300px;
    margin-left: 200px;
  }
  &-heading-container {
    display: flex;
    align-items: center;
  }
  &-heading {
    text-decoration: uppercase;
    color: #e4e3e3;
    display: flex;
    align-items: center;
    position: relative;

    &::after {
      content: "";
      display: block;
      height: 1px;
      width: 400px;
      background-color: #e4e3e3;
      margin-left: 15px;
    }
  }
  &-content-container {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    padding: 30px;
    width: 80%;
  }

  &-content {
    font-size: 15px;
    text-align: left;
    color: #e4e3e3;
  }

  &-tech-container {
    display: grid;
    grid-template-columns: minmax(140px, 200px) minmax(140px, 200px) minmax(
        140px,
        200px
      );
    margin-top: 20px;
  }

  &-tech {
    position: relative;
    margin-bottom: 10px;
    padding-left: 20px;
    font-size: 14px;
    color: #63beff;

    ::before {
      content: "";
      position: absolute;
      left: 0;
      color: #e4e3e3;
      font-size: 14px;
      line-height: 12px;
    }
  }
}
</style>
