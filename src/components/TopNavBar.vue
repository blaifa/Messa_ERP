
<template>
  <nav class="top-navbar">
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Services</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>
</template>

<script setup>
// import { reactive } from "vue";

// const state = reactive({ count: 0, display_article: false });

// function toggleActive() {
//   state.display_article = !state.display_article;
// }
</script>

<style scoped>
.top-navbar {
  display: flex;
  flex-direction: row;
  background-color: #a8a8a8;
  height: 11%;
  width: 100%;
  position: fixed;
  top: 0;
  left: 11%;
}

.top-navbar ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

.top-navbar li {
  display: inline-block;
  padding: 10px;
}

.top-navbar li a {
  text-decoration: none;
  color: #000;
}

.top-navbar li a:hover {
  background-color: #ccc;
}
</style>
