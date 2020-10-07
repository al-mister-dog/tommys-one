<template>
  <div id="app">
    <the-header></the-header>
      <main-image>
      </main-image>
      <fest-info></fest-info>
      <fest-image></fest-image>
      <the-videos></the-videos>
      <the-bio></the-bio>
      <the-footer></the-footer>
  </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue'
import MainImage from './components/MainImage.vue'
import FestInfo from './components/FestInfo.vue'
import FestImage from './components/FestImage.vue'
import TheVideos from './components/TheVideos.vue'
import TheBio from './components/TheBio.vue'
import TheFooter from './components/TheFooter'
export default {
  name: 'App',
  components: {
    TheHeader,
    MainImage,
    FestInfo,
    FestImage,
    TheVideos,
    TheBio,
    TheFooter
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0;
}
* {
  box-sizing: border-box;
}
body {
  margin: 0;
  padding: 0;
  background-image: linear-gradient(to bottom, black 0, black 15%, #593e3d 50%, black 100%);
}
</style>
