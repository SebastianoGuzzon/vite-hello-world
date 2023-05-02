<template>
  <h1 class="title">{{ titolo }}</h1>
</template>

<script>
export default {
  data() {
    return {
      titolo: 'La mia prima app con Vite!'
    }
  }
}
</script>

<style scoped>
.title {
  color: rgba(80, 167, 84, 0.432);
}

.title {
  font-style: oblique;
}
</style>