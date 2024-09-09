<script>
export default {
  data() {
    return { 
      message: 'Vite Hello World'
     }
  }
}
</script>

<template>
  <header>
    <h1>
      {{ message }}
    </h1>
  </header>
</template>

<style scoped>
header {
  background-color: aquamarine;
  text-align: center;
}

h1 {
  color: lightcoral;
  padding: 20px;
}
</style>
