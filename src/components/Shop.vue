<script setup>
import Product3 from "./Product3.vue";
</script>

<template>
  <div class="">
    <h2 class="text-[28px] mb-6">Магазины для вас</h2>
    <div class="grid grid-cols-3 gap-7 mb-20">
      <Product3 v-for="Items in 1" />
    </div>
  </div>
</template>

<style lang="scss" scoped></style>
