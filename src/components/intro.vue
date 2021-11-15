<template>
  <!-- Intro start -->
  <section class="intro">
    <div class="container">
      <div class="section__inner">
        <h1 class="intro__title">
          <div>ОРГАНИЧЕСКОЕ</div>
          <div>НАНО-УДОБНИЕ</div>
          <div>ДОБРИВО</div>
        </h1>
      </div>
    </div>
  </section>
  <!-- Intro end -->
</template>

<style lang="scss">
.intro {
  width: 100%;
  min-height: 449px;
  margin-top: -30px;
  padding-top: 30px;
  background-image: url("./../assets/images/background_main.jpg");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}

.intro__title {
  width: 100%;
  max-width: 607px;
  padding-top: 245px;
  margin-left: 90px;

  & div {
    color: #fff;
    font-size: 3.75rem;
    font-weight: 400;
    line-height: 0.9;

    &:nth-child(2) {
      padding-left: 110px;
    }

    &:nth-child(3) {
      padding-left: 160px;
    }
  }
}
</style>
