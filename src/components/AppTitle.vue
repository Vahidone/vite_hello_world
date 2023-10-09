<script>
export default {
  name: "Title",
  data() {
    return {
      titolo: "La mia prima app con Vite!",
    };
  },
};
</script>

<template>
  <h1>{{ titolo }}</h1>
</template>

<style scoped>
h1 {
  margin-top: 100px;
  text-align: center;
  color: blue;
}
</style>
