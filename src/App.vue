<template>
  <div id="app">
    <!-- Header start -->
    <Header />
    <!-- Header end -->

    <div class="page">
      <!-- Intro start -->
      <Intro />
      <!-- Intro end -->

      <!-- Benefit start  -->
      <Benefit />
      <!-- Benefit end -->
    </div>
  </div>
</template>

<script>
import { Header, Intro, Benefit } from "./components";

export default {
  name: "App",
  components: {
    Header,
    Intro,
    Benefit,
  },
};
</script>
