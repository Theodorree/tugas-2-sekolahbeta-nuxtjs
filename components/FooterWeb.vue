<template>
  <footer class="footer">
    <div class="container">
      <div class="footer-content">
        <p class="footer-text">&copy; 2023 E-commerce. All Rights Reserved</p>
        <div class="developer-info">
          <h2 class="developer-name">Developed by Theodorus</h2>
        </div>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.footer {
  background-color: #2c3e50;
  color: white;
  padding: 40px 0;
}

.footer-content {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.footer-text {
  font-size: 14px;
  margin-bottom: 20px;
}

.developer-info {
  text-align: center;
}

.developer-name {
  font-size: 24px;
  margin-bottom: 5px;
}

.developer-description {
  font-size: 14px;
  color: #95a5a6;
}
</style>
