<template>
  <header class="header">
    Todo List
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
  </header>
</template>
<script>
export default {};
</script>
<style scoped>
.header {
  background: whitesmoke;
  color: #333;
  font-weight: bold;
  text-align: center;
  padding: 10px;
}
.header a {
  color: #333;
  padding-right: 5px;
  text-decoration: none;
}
</style>
