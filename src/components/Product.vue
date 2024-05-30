<script setup>
const products = [
  {
    id: 1,
    image: "../src/assets/boy 5.jpg",
    discount: "-25%",
    price: "2 399 ₽",
    oldPrice: "3 790 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 06 абстракция",
  },
  {
    id: 2,
    image: "../src/assets/boy 5.jpg",
    discount: "-25%",
    price: "2 399 ₽",
    oldPrice: "3 790 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 06 абстракция",
  },
  {
    id: 3,
    image: "../src/assets/boy 5.jpg",
    discount: "-25%",
    price: "2 399 ₽",
    oldPrice: "3 790 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 06 абстракция",
  },
  {
    id: 4,
    image: "../src/assets/boy 5.jpg",
    discount: "-25%",
    price: "2 399 ₽",
    oldPrice: "3 790 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 06 абстракция",
  },
  {
    id: 5,
    image: "../src/assets/boy 5.jpg",
    discount: "-25%",
    price: "2 399 ₽",
    oldPrice: "3 790 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 06 абстракция",
  },
  {
    id: 6,
    image: "../src/assets/boy 5.jpg",
    discount: "-25%",
    price: "2 399 ₽",
    oldPrice: "3 790 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 06 абстракция",
  },
  {
    id: 7,
    image: "../src/assets/boy 5.jpg",
    discount: "-25%",
    price: "2 399 ₽",
    oldPrice: "3 790 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 06 абстракция",
  },
  {
    id: 8,
    image: "../src/assets/boy 5.jpg",
    discount: "-25%",
    price: "2 399 ₽",
    oldPrice: "3 790 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 06 абстракция",
  },
  {
    id: 9,
    image: "../src/assets/boy 5.jpg",
    discount: "-25%",
    price: "2 399 ₽",
    oldPrice: "3 790 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 06 абстракция",
  },
  {
    id: 10,
    image: "../src/assets/boy 5.jpg",
    discount: "-25%",
    price: "2 399 ₽",
    oldPrice: "3 790 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 06 абстракция",
  },
  {
    id: 11,
    image: "../src/assets/boy 5.jpg",
    discount: "-25%",
    price: "2 399 ₽",
    oldPrice: "3 790 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 06 абстракция",
  },
  {
    id: 12,
    image: "../src/assets/boy 5.jpg",
    discount: "-25%",
    price: "2 399 ₽",
    oldPrice: "3 790 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 06 абстракция",
  },
];

</script>

<template>

  
  <!-- <div class="container"> -->
  <div
  
    v-for="product in products"
    :key="product.id"
    class="w-[200.5px] rounded-md p-3 bg-slate-100 relative"
  >
    <img class="w-[177px]" :src="product.image" alt="product" />
    <span
      class="absolute top-4 left-[155px] border-red-400 border rounded-3xl px-[3px] font-medium text-[10px]"
      >{{ product.discount }}</span
    >
    <div class="flex gap-6 pt-4 items-center">
      <p class="text-sm font-medium text-[#FF4343]">{{ product.price }}</p>
      <p class="text-[10px] pt-1 line-through decoration-red-500">
        {{ product.oldPrice }}
      </p>
    </div>
    <p class="w-[157px]">
      {{ product.description }}
    </p>
  </div>
</template>

<style scoped></style>
