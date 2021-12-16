<template>
  <navbar />
  <Header />
  <Video />
  <appdesc />
  <apps />
  <Footer />
</template>

<script>
import navbar from "./components/navbar.vue";
import Header from "./components/Header.vue";
import Video from "./components/Video.vue";
import appdesc from "./components/app-desc.vue";
import apps from "./components/apps.vue";
import Footer from "./components/footer.vue";
import "./scss/styles.css";
import "../node_modules/bootstrap/dist/css/bootstrap.min.css";

export default {
  name: "App",
  components: {
    navbar,
    Header,
    Video,
    appdesc,
    apps,
    Footer,
  },
};
</script>

<style lang="scss"></style>
