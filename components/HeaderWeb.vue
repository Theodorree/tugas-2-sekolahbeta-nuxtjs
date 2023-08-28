<template>
  <header class="header">
    <div class="header-content">
      <h1 class="logo">E-commerce</h1>
      <nav class="nav-links">
        <router-link to="/" class="nav-link">Beranda</router-link>
        <router-link to="/about" class="nav-link">Tentang</router-link>
        <router-link to="/contact" class="nav-link">Kontak</router-link>
      </nav>
    </div>
  </header>
</template>

<style scoped>
.header {
  background-color: #2c3e50;
  color: white;
  padding: 20px 0;
}

.header-content {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1200px;
  margin: 0 auto;
}

.logo {
  font-size: 28px;
  font-weight: bold;
}

.nav-links {
  display: flex;
  gap: 20px;
}

.nav-link {
  color: white;
  text-decoration: none;
  padding: 10px;
  border-radius: 5px;
  transition: background-color 0.3s, color 0.3s;
}

.nav-link:hover {
  background-color: #e74c3c;
  color: white;
}
</style>
