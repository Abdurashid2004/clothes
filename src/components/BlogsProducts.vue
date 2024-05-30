<script setup>
import Product from "./Product.vue";
import Product2 from "./Product2.vue";
</script>

<template>
  <div class="container mb-6">
    <div>
      <h2 class="text-[28px] py-5">Успей купить</h2>
      <div class="grid grid-cols-6 gap-8">
        <Product v-for="products in 1" />
        <!-- <Product v-for="products2 in 1" /> -->
      </div>
    </div>
    <div>
      <button
        class="float-right px-14 py-3 border-2 border-red-400 mt-6 text-sm font-medium hover:border-blue-400"
      >
        Все товары
      </button>
    </div>
    <div class="mt-10">
      <h2 class="text-[28px] py-5">Новинки</h2>
      <div class="grid grid-cols-6 gap-8">
        <!-- <Product v-for="products in 1" /> -->
        <Product2 v-for="products in 1" />
      </div>
    </div>
    <div>
      <button
        class="float-right px-14 py-3 border-2 border-red-400 mt-6 text-sm font-medium hover:border-blue-400"
      >
        Все товары
      </button>
    </div>
  </div>
</template>

<style lang="scss" scoped></style>
