<script setup>
const Items = [
  {
    id: 1,
    image: "../src/assets/logo4.jpg",
    name: "Marple",
    image1: "../src/assets/hat 1.jpg",
    image2: "../src/assets/boy 3.jpg",
    image3: "../src/assets/phone 5.jpg",
  },
  {
    id: 1,
    image: "../src/assets/logo4.jpg",
    name: "Huawei",
    image1: "../src/assets/hat 1.jpg",
    image2: "../src/assets/boy 3.jpg",
    image3: "../src/assets/phone 5.jpg",
  },
  {
    id: 1,
    image: "../src/assets/logo4.jpg",
    name: "Berlingo",
    image1: "../src/assets/hat 1.jpg",
    image2: "../src/assets/boy 3.jpg",
    image3: "../src/assets/phone 5.jpg",
  },
  {
    id: 1,
    image: "../src/assets/logo4.jpg",
    name: "U-kwai",
    image1: "../src/assets/hat 1.jpg",
    image2: "../src/assets/boy 3.jpg",
    image3: "../src/assets/phone 5.jpg",
  },
  {
    id: 1,
    image: "../src/assets/logo4.jpg",
    name: "Lassie",
    image1: "../src/assets/hat 1.jpg",
    image2: "../src/assets/boy 3.jpg",
    image3: "../src/assets/phone 5.jpg",
  },
  {
    id: 1,
    image: "../src/assets/logo4.jpg",
    name: "Densel",
    image1: "../src/assets/hat 1.jpg",
    image2: "../src/assets/boy 3.jpg",
    image3: "../src/assets/phone 5.jpg",
  },
];
</script>

<template>
  <div
    v-for="(item, index) in Items"
    :key="index"
    class="w-[296px] h-[208px] bg-slate-200 pt-8"
  >
    <div class="flex items-center gap-4 pl-5">
      <img :src="item.image" alt="product" />
      <h3 class="text-2xl">{{ item.name }}</h3>
    </div>
    <div class="flex items-center pt-6 pl-5 gap-2">
      <img :src="item.image1" alt="product" />
      <img :src="item.image2" alt="product" />
      <img :src="item.image3" alt="product" />
    </div>
  </div>
</template>

<style lang="scss" scoped></style>
