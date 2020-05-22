<template>
  <nav class="container">
    <ul class="navbar">
      <li class="navbar-item">Home</li>
      <li class="navbar-item">Blog</li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: "nav",
};
</script>

<style>
.container {
  position: relative;
  width: 100%;
  max-width: 960px;
  margin: 0 auto;
  padding: 0 20px;
  box-sizing: border-box;
}
.navbar {
  list-style-type: none;
  display: flex;
}
.navbar-item {
  position: relative;
  float: left;
  margin-bottom: 0;
  margin-left: 5px;
  margin-right: 5px;
}
</style>
