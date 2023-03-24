<script>
import AppTitle from './components/AppTitle.vue';
import AppJumbotron from './components/AppJumbotron.vue';
export default {
  components: {
    AppTitle,
    AppJumbotron
  }
}
</script>

<template>
  <div>
    <AppTitle />
    <AppJumbotron />
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
