<script setup>
// import { ref, reactive, onMounted, onUnmounted, computed } from "vue";
import Header from "./components/Header.vue";
import Shop from "./components/Shop.vue";
import Navbar from "./components/Navbar.vue";
import BlogsProducts from "./components/BlogsProducts.vue";

// let message = "Message";
// const name = ref("Bobur");

// const user = reactive({
//   name: "Jumavoy",
//   age: 21,
// });

// function changeMessage() {
//   message = "New Message";
//   name.value = "Abdurashid";
//   user.name = "Sattor";
// }

// onMounted(() => {
//   console.log("Mounted");
// });

// onUnmounted(() => {
//   console.log("o'ldi");
// });

// const arr = reactive([1, 2, 3, 4, 5]);

// const reverseArr = computed(() => {
//   return arr.slice().reverse();
// });

// watch;
</script>

<template>
  <div>
    <Navbar />
    <Header />
    <div class="grid grid-cols-6 gap-8">
      <BlogsProducts class="col-span-6" />
    </div>
    <div class="container grid grid-cols-4">
      <Shop class="col-span-3" />
    </div>
    <!-- <h1>Hello Composition API</h1>

    <h1>{{ message }}</h1>
    <h1>{{ name }}</h1>
    <p>{{ reverseArr }}</p>

    <h1>Object name: {{ user.name }}</h1>

    <button @click="changeMessage">Change</button>

    <input type="text" v-model="name" /> -->
  </div>
</template>

<style scoped></style>
