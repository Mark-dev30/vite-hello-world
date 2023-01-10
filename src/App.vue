<script>
import AppHero from './components/AppHero.vue';
import AppTitle from './components/AppTitle.vue';


export default {
  components: {
    AppTitle,
    AppHero
  }
}
</script>

<template>

  <AppHero class="jumbo"></AppHero>
  <AppTitle class="title"></AppTitle>
</template>

<style scoped>
.jumbo {
  position: relative;
}

.title {
  text-align: center;
  position: absolute;
  bottom: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
</style>
