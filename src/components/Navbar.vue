<template>
  <nav class="navbar" :class="{ 'sticky': isSticky }">
      <img src="@/assets/logo.png" alt="logo" class="navbar-logo"/>
      <div class="moto">Layanan Jasa Desin Grafis Berkualitas</div>
  </nav>
</template>

<script>
export default {
  name: 'AppNavbar',
}
</script>

<style scoped>
.navbar {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  z-index: 1000;
  transition: top 0.3s ease-in-out;
  display: flex;
  font-size: 15px;
  background-color: #222;
  color: white;
  padding: 10px 0;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  align-items: center;
}
.navbar-logo {
  max-height: 30px;
  margin-left: 20px;
}
.moto {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  color: #f1eded;
  margin-left: 20px;
  margin-top: 3px;
}
</style>
