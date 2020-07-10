<template>
  <div class="header">
    <h1>
      <span class="header__greet">
        Hello
      </span>
      <span class="header__name">
        I'm Ibrahim Abdulkareem.
      </span>
      <span class="header__work">
        I'm a Software Engineer.
      </span>
    </h1>
  </div>
</template>

<style lang="scss" scoped>
.header {
  display: flex;
  margin-top: 200px;
  margin-right: 200px;
  justify-content: center;

  &__greet {
    display: block;
    text-decoration: uppercase;
    font-size: 20px;
    line-height: 30px;
    margin-right: 505px;
    color: #da22ff;
  }

  &__name {
    display: block;
    text-decoration: uppercase;
    font-size: 40px;
    font-weight: 400;
    margin-right: 115px;
  }

  &__work {
    display: block;
    text-decoration: uppercase;
    font-size: 50px;
    font-weight: 700;
    color: #e4e3e3;
    margin-right: 50px;
  }
}
</style>
