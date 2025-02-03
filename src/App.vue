<template>
  <div class="dark-theme">
    <header class="header">
      <div class="header-content">
        <i class="icon fas fa-shield-alt"></i>
        <h1 class="title">Военно-политическая игра</h1>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {

  }
}
</script>

<style>

body {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
  background-color: #121212;
  color: #ffffff; 
}

.dark-theme {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
}

.header {
  width: 100%;
  padding: 20px;
  background-color: #1f1f1f; 
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2); 
}

.header-content {
  display: flex;
  align-items: center;
  max-width: 1200px;
  margin: 0 auto;
}

.icon {
  font-size: 2.6rem; 
  color: #ffffff; 
  margin-right: 15px; 
}

.title {
  font-size: 2.6rem;
  font-weight: bold;
  margin: 0;
  color: #ff5722; 
  text-transform: uppercase;
}
</style>