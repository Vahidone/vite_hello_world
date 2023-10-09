<script>
export default {
  name: "jumbotron",
  data() {
    return {};
  },
};
</script>

<template>
  <div class="container">
    <h1>ciao jumbotron</h1>
    <figure>
      <img src="/163822766-57cf8569-bf06-42d3-be81-835ba3c10e09.jpg" alt="" />
    </figure>
  </div>
</template>

<style scoped>
figure {
  width: 450px;
  height: 400px;
  margin: 20px auto;
}
img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.container {
  background-color: lightblue;
  height: 700px;
  padding: 100px;
}

h1 {
  color: rgb(65, 13, 13);
  text-align: center;
}
</style>
