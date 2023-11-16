<template>
    <footer>
      <p>&copy; 2023 Your Portfolio. All rights reserved.</p>
      <a href="https://www.linkedin.com/in/sachinsingh103/" target="_blank" rel="noopener noreferrer">
        <img src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/svgs/brands/linkedin.svg" alt="LinkedIn">
      </a>
      <a href="https://github.com/103Sachin" target="_blank" rel="noopener noreferrer">
        <img src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/svgs/brands/github.svg" alt="GitHub">
      </a>
    </footer>
</template>
  
<script>
  export default {
    // Component logic goes here
    name: 'Footer-Section'
  }
</script>
  
<style scoped>
  
  footer {
  background-color: #333;
  color: white;
  padding: 1rem;
  text-align: center;
}

p {
  margin: 0;
}
.external-links {
  margin-top: 1rem;
  display: flex;
  justify-content: center;
}

a {
  color: white;
  margin: 0 1rem;
  text-decoration: none;
}

a:hover {
  color: #61dafb;
}
</style>

  