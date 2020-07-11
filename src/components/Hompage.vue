<template>
  <div class="header">
    <h1>
      <span class="header__greet">Hello</span>
      <span class="header__name">I'm Ibrahim Abdulkareem.</span>
      <span class="header__work">I'm a Software Engineer.</span>
    </h1>
  </div>
</template>

<style lang="scss" scoped>
.header {
  display: flex;
  margin-top: 200px;
  margin-left: 200px;

  &__greet {
    display: block;
    font-size: 20px;
    line-height: 30px;
    //margin-right: 505px;
    color: #da22ff;
  }

  &__name {
    display: block;
    font-size: 40px;
    font-weight: 400;
    color: #e4e3e3;
    //margin-right: 115px;
  }

  &__work {
    display: block;
    font-size: 70px;
    font-weight: 700;
    color: #e4e3e3;
    // margin-right: 50px;
  }
}
</style>
