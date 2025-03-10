<script setup></script>

<template>
  <footer class="footer">
    <div class="footer-container">
      <div class="footer-info">
        <p><strong>ADDRESS:</strong> 6391 Elgin St. Celina, Delaware 10299</p>
        <p><strong>PHONE:</strong> +84 1102 2703</p>
        <p><strong>EMAIL:</strong> hello@thebox.com</p>
        <div class="footer-logo">
          <img src="./../assets/logo.png" alt="" />
        </div>
      </div>

      <div class="footer-news-social">
        <div class="footer-newsletter">
          <p><strong>NEWSLETTER:</strong></p>
          <input type="email" placeholder="Your email here" />
          <button>Subscribe</button>
        </div>

        <div class="footer-social">
          <p><strong>SOCIAL:</strong></p>
          <div class="social-icons">
            <a href="#"><img src="./../assets/icon-fb.png" alt="Facebook" /></a>
            <a href="#"
              ><img src="./../assets/icon-linkedin.png" alt="LinkedIn"
            /></a>
            <a href="#"
              ><img src="./../assets/icon-twitter.png" alt="Twitter"
            /></a>
          </div>
        </div>
      </div>
    </div>

    <div class="footer-bottom">
      <p>TheBox Company © 2022. All Rights Reserved</p>
    </div>
  </footer>
</template>

<style scoped>
.footer {
  background-color: #fff;
  border-top: 1px solid #ddd;
}

.footer-container {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  flex-wrap: wrap;
}

.footer-info {
  text-align: left;
  padding: 50px;
}

.footer-info p {
  margin-bottom: 10px;
  color: #333;
}

.footer-logo img {
  width: 120px;
  margin-top: 10px;
}

.footer-news-social {
  padding: 50px;
}

.footer-newsletter {
  text-align: left;
}

.footer-newsletter input {
  padding: 8px;
  width: 200px;
  border: 1px solid #ddd;
  border-radius: 4px;
  margin-top: 5px;
}

.footer-newsletter button {
  background-color: #d17a63;
  color: white;
  border: none;
  padding: 8px 12px;
  cursor: pointer;
  border-radius: 4px;
  margin-left: 5px;
}

.footer-newsletter button:hover {
  background-color: #b55f47;
}

.footer-social {
  text-align: left;
}

.social-icons {
  display: flex;
  gap: 15px;
  margin-top: 5px;
}

.social-icons a img {
  width: 30px;
  height: 30px;
}

.footer-bottom {
  text-align: center;
  background-color: #0049a5;
  color: white;
  padding: 10px 0;
  margin-top: 20px;
}
</style>
