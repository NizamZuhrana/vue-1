<script setup>
defineProps({
  title: String,
  description: String,
  icon: String,
});
</script>

<template>
  <div class="card">
    <div class="icon">{{ icon }}</div>
    <!-- <img :src="icon" alt=""> -->
    <h3>{{ title }}</h3>
    <p>{{ description }}</p>
  </div>
</template>

<style scoped>
.card {
  border: 1px solid #ddd;
  padding: 20px;
  border-radius: 8px;
  text-align: center;
  width: 300px;
  transition: 0.3s;
}

.card:hover {
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
}

.icon {
    font-size: 30px;
    margin-bottom: 10px;
    color: #d17a63;
}

h3 {
  color: #333;
  font-size: 20px;
  margin-bottom: 10px;
}

p {
  color: #666;
  font-size: 14px;
}
</style>
