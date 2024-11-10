<template>
    <aside>
      <!-- Содержимое боковой панели -->
      <ul>
        <li><router-link to="/dashboard">Дашборд</router-link></li>
        <li><router-link to="/settings">Настройки</router-link></li>
        <!-- Другие пункты меню -->
      </ul>
    </aside>
  </template>
  
  <script>
  export default {
    name: 'SidebarComponent',
  };
  </script>
  
  <style scoped>
  /* Стили для Sidebar */
  aside {
    width: 200px;
    background-color: #eaeaea;
    padding: 10px;
  }
  </style>
  