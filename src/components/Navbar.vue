<script setup></script>

<template>
  <nav class="navbar">
    <div class="logo">
      <img src="./../../public/logo-navbar.png" alt="" />
      <img src="./../../src/assets/TheBox.png" alt="">
    </div>
    <div>
      <ul class="nav-links">
        <li><a href="#">Home</a></li>
        <li><a href="#">About Us</a></li>
        <li><a href="#">Projects</a></li>
        <li><a href="#">Services</a></li>
        <li class="contact"><a href="#">Contact Us</a></li>
      </ul>
    </div>
  </nav>
</template>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 50px;
  background-color: white;
  color: #333;
  border-bottom: 1px solid #ddd;
}

.logo {
  font-size: 24px;
  display: flex;
  align-items: center;
  font-weight: bold;
}

.logo img {
  width: 40px;
  height: auto;
  margin-right: 10px;
}

.logo img:last-child {
  width: 100px; /* Samakan ukurannya dengan logo-navbar */
  height: auto;
  object-fit: contain; /* Pastikan gambar tetap proporsional */
}

.nav-links {
  display: flex;
  justify-content: space-between;
  gap: 30px;
  list-style: none;
}

.nav-links li {
  display: inline;
}

.nav-links a {
  text-decoration: none;
  color: #333;
  font-size: 18px;
  font-weight: 500;
}

.nav-links .contact {
  color: #d17a63;
  font-weight: bold;
}
</style>
