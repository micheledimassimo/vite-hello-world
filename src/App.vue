<script>

import AppHeader from './components/AppHeader.vue';


export default {
  data() {
    return { 
      count: 0 
    }
  },
  components: {
    AppHeader
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
    <AppHeader />
    <button @click="incrementCount()">
      {{ count }}
    </button>
  </div>
</template>

<style scoped>

</style>
