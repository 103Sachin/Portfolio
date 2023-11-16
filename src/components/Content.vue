<template>
    <main>
      <!-- Content goes here -->
      <router-view></router-view>
    </main>
  </template>
  
  <script>
  export default {
    // Component logic goes here
    name: 'Content-Section'
  }
  </script>
  
  <style scoped>
  
  main {
  max-width: 800px;
  margin: 0 auto;
  padding: 1rem;
}
  </style>
  