<template>
    <header>
      <h1 class="h1-text">СКОРО БУДЕТ!</h1>
      <nav>
        <!-- Здесь могут быть ссылки на маршруты -->
        <!-- <router-link to="/home">Главная</router-link>
        <router-link to="/about">О нас</router-link> -->
        <!-- Другие ссылки -->
      </nav>
    </header>
  </template>
  
  <script>
  export default {
    name: 'HeaderComponent',
  };
  </script>
  
  <style scoped>
  /* Стили для Header */
  .h1-text {
    text-align: center;
  }

  header {
    background-color: #f8f8f8;
    padding: 10px;
  }
  </style>
  