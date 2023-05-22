<template>
  <div class="lateral-navbar">
    <ul class="navbar-list">
      <li class="navbar-list-item">
        <a>ARTICLE</a>
        <ul class="navbar-list-item-subitem">
          <li><a href="/Article">Liste des articles</a></li>
          <li><a href="/Article">Subitem 2</a></li>
          <li><a href="#">Subitem 3</a></li>
        </ul>
      </li>
      <!-- add more list items as needed -->
      <li class="navbar-list-item">
        <a>ARTICLE</a>
        <ul class="navbar-list-item-subitem">
          <li><a href="/">Subitem 1</a></li>
          <li><a href="/Article">Subitem 2</a></li>
          <li><a href="#">Subitem 3</a></li>
        </ul>
      </li>
    </ul>
  </div>
</template>

<script setup>
// import { reactive } from "vue";

// const state = reactive({ count: 0, display_article: false });

// function toggleActive() {
//   state.display_article = !state.display_article;
// }
</script>

<style scoped>
.lateral-navbar {
  display: flex;
  flex-direction: column;
  background-color: #a8a8a8;
  height: 89%;
  width: 11%;
  position: fixed;
  top: 11%;
  left: 0;
  overflow: auto;
}

.navbar-list {
  list-style: none;
  margin: 0;
  padding: 0;
}

.navbar-list li a {
  display: block;
  padding: 10px;
  text-decoration: none;
  color: #333;
}

.navbar-list-item {
  border-bottom: 1px solid #ddd;
}

.navbar-list-item-subitem {
  list-style: none;
}

.navbar-list-item-subitem a:hover {
  color: #ddd;
}
</style>
