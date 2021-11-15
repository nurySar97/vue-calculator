<template>
  <div id="app">
    <Header />
    <div class="page">
      <Intro />
    </div>
  </div>
</template>

<script>
import { Header, Intro } from "./components";

export default {
  name: "App",
  components: {
    Header,
    Intro,
  },
};
</script>
