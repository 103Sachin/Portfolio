<template>
  <header>
    <nav>
      <ul>
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/about">About</router-link></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'Header-Section'
  // Component logic goes here
}
</script>

<style scoped>

header {
  background-color: #333;
  padding: 1rem;
  color: white;
}

nav {
  display: flex;
  justify-content: space-between;
}

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  display: flex;
}

li {
  margin-right: 1rem;
}

a {
  text-decoration: none;
  color: white;
  font-weight: bold;
}

a:hover {
  color: #61dafb;
}
</style>
