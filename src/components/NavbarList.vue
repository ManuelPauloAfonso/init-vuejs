<script setup>


</script>


<template>
    <nav>
      <ul class="menu">
        <li><a href="#">Página Inicial</a></li>
        <li><a href="#">Sobre</a></li>
        <li><a href="#">Serviços</a></li>
        <li><a href="#">Contato</a></li>
      </ul>
    </nav>
</template>

<style scoped>
nav {
  background-color: #f2f2f2;
}

.menu {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

.menu li {
  display: inline-block;
}

.menu li a {
  display: block;
  padding: 1rem;
  text-decoration: none;
  color: #333;
}

.menu li a:hover {
  background-color: #ddd;
}
</style>