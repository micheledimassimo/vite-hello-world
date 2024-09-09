<script>
export default {
  data() {
    return { 
        Image: './jumbotron-min.jpg'
     }
  }
}
</script>

<template>
  <div>
    <img :src="Image" :alt="Image">
  </div>
</template>

<style scoped>
div {
    margin: 0 auto;
    max-width: 1000px;
}
img {
    object-fit: cover;
}
</style>
