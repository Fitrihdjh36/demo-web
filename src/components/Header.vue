<template>
    <header class="header">
        <div class="header-background"></div>
      <div class="header-content">
        <div class="content-box">
            <h1>INSPIRAZI DESIGN</h1>
            <p>Layanan Jasa Desain Grafis Berkualitas</p>
        </div>
        </div>
    </header>
  </template>
  
  <script>
  export default {
    name: 'AppHeader',
  };
  </script>
  
  <style scoped>
  .header {
    position: relative;
    background-color: rgba(0, 0, 0, 0.5);
    color: white;
    text-align: center;
    margin-top: -10px;
  }
  .header-background {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: url("@/assets/logo4.jpg"); 
    background-size: cover;
    background-position: center;
    z-index: -1;
  }
  .header-content {
    padding: 100px 0;
  }
  .content-box {
    padding: 20px;
  }
  .header h1 {
    margin: 0;
    font-size: 60px;
  }
  .header p {
    margin: 0;
    font-size: 20px;
  }
  </style>
  