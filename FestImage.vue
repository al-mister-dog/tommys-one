<template>
  <a :href="link">
    <div class="container"></div>
  </a>
</template>

<script>
export default {
  data() {
    return {
      link: 'https://www.fairportconvention.com/'
    }
  }
}
</script>

<style scoped>
main {
  height: 150vh;
}
.container {
  height: 100vh;
  max-width: 680px;
  margin-left: auto;
  margin-right: auto;
  background-image: url("../assets/fairport.jpeg");
  background-size: contain;
  background-repeat: no-repeat;
  background-position: center;
}
</style>