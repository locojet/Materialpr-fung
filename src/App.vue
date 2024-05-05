<script setup>
import PageLoader from './components/PageLoader.vue';
import CallMail from './components/CallMail.vue';
import Navigation from './components/Navigation.vue';
import VideoAbspann from './components/VideoAbspann.vue';
import Zulassung from './components/Zulassung.vue';
import Dienstleistungen from './components/Dienstleistungen.vue';
import Jobs from './components/Jobs.vue';
import Footer from './components/Footer.vue';
import About from './components/About.vue';
import Formular from './components/Formular.vue';

</script>

<template>
  <div id="app" class="grid-container">
  <PageLoader />
  <navigation />
  <VideoAbspann />
  <Zulassung />
  <Dienstleistungen />
  <Jobs />
  <About />
  <CallMail />
  <Formular />
  <Footer />
</div>
</template>

<style scoped>
#sec-1 {
  margin-top: -3rem;
}
*{
  transition: all 0.5s ease-in-out;
}
</style>
