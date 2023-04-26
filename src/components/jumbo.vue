<script>
export default {
  name: 'Jumbo',
  data() {
    return {
      title: 'Jumbo'
    }
  }
}
</script>

<template>
  <div class="jumbotron-container">
    <div class="jumbotron">
      <h1 class="display-4">{{ title }}</h1>
      <button class="btn btn-primary">Scopri di più</button>
    </div>
  </div>
</template>

<style scoped>
.jumbotron-container {
  width: 1000px;
  margin: 0 auto;
}

.jumbotron {
  padding: 2rem 1rem;
  margin-bottom: 2rem;
  background-color: darkgoldenrod;
  height: 200px;
  border-radius: 10px;
  text-align: center;
  width: 100%;
}

.display-4 {
  font-size: 2.5rem;
  font-weight: 300;
  margin-bottom: 1rem;
  color: blue;
}

.btn {
  display: inline-block;
  font-weight: 400;
  color: #fff;
  text-align: center;
  vertical-align: middle;
  cursor: pointer;
  background-color: #007bff;
  border: 1px solid transparent;
  padding: 0.5 0.5rem;
  font-size: 1rem;
  line-height: 1.5;
  border-radius: 0.25rem;
  text-decoration: none;
}

.btn-primary:hover {
  background-color: #0056b3;
  border-color: #004499;
}

</style>
