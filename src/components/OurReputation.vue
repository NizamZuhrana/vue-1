<script setup>
import { ref } from "vue";
import Card from "./Card.vue";
import Icon from "./../assets/icon.png";
import Icon1 from "./../assets/icon-1.png";
import Icon2 from "./../assets/icon-2.png";

const Data = [
  {
    id: 1,
    // icon: "🎧",
    icon: Icon,
    title: "Best Services",
    description:
      "lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.",
  },
  {
    id: 2,
    // icon: "👥",
    icon: Icon1,
    title: "Best Teams",
    description:
      "lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.",
  },
  {
    id: 3,
    // icon: "✏️",
    icon: Icon2,
    title: "Best Design",
    description:
      "lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.",
  },
];
</script>

<template>
  <div class="our-reputation">
    <h1>OUR REPUTATION</h1>
    <div class="cards-container">
      <div v-for="(item, index) in Data">
        <Card
          :key="item.id"
          :title="item.title"
          :description="item.description"
          :icon="item.icon"
        />
      </div>
    </div>
  </div>
</template>

<style scoped>
.our-reputation {
  padding: 50px 20px;
  text-align: center;
}

.cards-container {
  display: flex;
  justify-content: center;
  gap: 20px;
  margin-top: 20px;
}
</style>
