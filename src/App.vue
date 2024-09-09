<script>

import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';



export default {
  data() {
    return { 
      count: 0 
    }
  },
  components: {
    AppTitle,
    AppHero
  },
  methods: {
    incrementCount() {
      this.count++;
    }
  }
}
</script>

<template>
  <div>
    <AppTitle />
    <button @click="incrementCount()">
      {{ count }}
    </button>
    <AppHero />
  </div>
</template>

<style scoped>

</style>
