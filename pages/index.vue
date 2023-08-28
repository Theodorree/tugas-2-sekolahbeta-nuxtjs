<template>
  <div class="container">
    <h1 class="header">Selamat Datang di Toko Online Kami!</h1>
    <p class="description">
      Temukan produk terbaik dan penawaran menarik hanya di toko kami. Kami
      menyediakan berbagai pilihan produk berkualitas untuk memenuhi kebutuhan
      Anda.Kami juga menyediakan berbagai penawaran spesial, diskon menarik, dan
      promo eksklusif yang akan membuat setiap pembelian menjadi lebih berharga.
      Dengan layanan pelanggan yang responsif dan ramah, kami berkomitmen untuk
      memberikan pengalaman berbelanja yang luar biasa bagi setiap pelanggan
      kami.
    </p>
    <ul class="menu">
      <li><a href="#">Explore</a></li>
      <li><a href="#">Promo</a></li>
      <li><a href="#">Produk Terbaru</a></li>
      <li><a href="#">Kategori</a></li>
    </ul>
  </div>
</template>

<script></script>

<style scoped>
.container {
  width: 75%;
  margin: 100px auto;
  text-align: center;
}

.header {
  font-size: 28px;
  margin-bottom: 10px;
}

.description {
  font-size: 18px;
  color: #666;
  margin-bottom: 20px;
}

.menu {
  list-style: none;
  padding: 0;
  margin-top: 20px;
}

.menu li {
  display: inline;
  margin-right: 20px;
}

.menu li:last-child {
  margin-right: 0;
}

.menu li a {
  padding: 10px 20px;
  text-decoration: none;
  background-color: #f5f5f5;
  color: #333;
  border-radius: 5px;
  transition: background-color 0.3s, color 0.3s;
}

.menu li a:hover {
  background-color: #333;
  color: #fff;
}
</style>
