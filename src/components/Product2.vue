<script setup>
const products = [
  {
    id: 1,
    image: "../src/assets/boy 5.jpg",
    price: "2 399 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 06 абстракция",
  },
  {
    id: 2,
    image: "../src/assets/boy 5.jpg",
    price: "2 399 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 06 абстракция",
  },
  {
    id: 3,
    image: "../src/assets/boy 5.jpg",
    price: "2 399 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 06 абстракция",
  },
  {
    id: 4,
    image: "../src/assets/boy 5.jpg",
    price: "2 399 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 06 абстракция",
  },
  {
    id: 5,
    image: "../src/assets/boy 5.jpg",
    price: "2 399 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 06 абстракция",
  },
  {
    id: 6,
    image: "../src/assets/boy 5.jpg",
    price: "2 399 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 06 абстракция",
  },
  {
    id: 7,
    image: "../src/assets/boy 5.jpg",
    price: "2 399 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 06 абстракция",
  },
  {
    id: 8,
    image: "../src/assets/boy 5.jpg",
    price: "2 399 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 06 абстракция",
  },
  {
    id: 9,
    image: "../src/assets/boy 5.jpg",
    price: "2 399 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 06 абстракция",
  },
  {
    id: 10,
    image: "../src/assets/boy 5.jpg",
    price: "2 399 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 06 абстракция",
  },
  {
    id: 11,
    image: "../src/assets/boy 5.jpg",
    price: "2 399 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 06 абстракция",
  },
  {
    id: 12,
    image: "../src/assets/boy 5.jpg",
    price: "2 399 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 06 абстракция",
  },
];

</script>

<template>

  
  <!-- <div class="container"> -->
  <div
  
    v-for="product in products"
    :key="product.id"
    class="w-[200.5px] rounded-md p-3 bg-slate-100"
  >
    <img class="w-[177px]" :src="product.image" alt="product" />
    <div class="flex gap-6 items-center">
      <p class="text-lg font-medium py-2">{{ product.price }}</p>
    </div>
    <p class="w-[157px]">
      {{ product.description }}
    </p>
  </div>
</template>

<style scoped></style>
