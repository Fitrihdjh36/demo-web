<template>
    <footer class="footer">
        <div class="footer-content">
          <!-- Kolom Kiri  -->
          <div class="left-column">
            <img src="@/assets/logo.png" alt="logo" class="logo" />
            <p>Kami sangat senang untuk dapat melayani Anda. Jika Anda tertarik untuk memesan layanan kami atau memiliki pertanyaan lebih lanjut, silakan untuk mengisi formulir kontak di bawah ini. Tim kami akan segera merespons permintaan Anda. Terima kasih atas minat Anda dalam layanan kami.</p>
          </div>
  
          <!-- Kolom Kanan (Formulir) -->
          <div class="right-column">
            <h2>Hubungi Kami</h2>
            <form @submit="submitForm">
              <div class="form-group">
                <label for="name">Nama</label>
                <input type="text" id="name" v-model="formData.name" required>
              </div>
              <div class="form-group">
                <label for="email">Email</label>
                <input type="email" id="email" v-model="formData.email" required>
              </div>
              <div class="form-group">
                <label for="message">Pesan</label>
                <textarea id="message" v-model="formData.message" required></textarea>
              </div>
              <button type="submit">Kirim</button>
            </form>
          </div>
        </div>
        <div class="footer-bottom">© Copyright Inspirazi Desain 2023. </div>
      </footer>
  </template>
  
  <script>
  export default {
    name: 'AppFooter',
    data() {
    return {
      formData: {
        name: '',
        email: '',
        message: ''
      }
    }
  },
  methods: {
    submitForm() {
      console.log('Data formulir yang akan dikirim:', this.formData);
      this.formData = {
        name: '',
        email: '',
        message: ''
      }
    }
  }
  }
  </script>
  
  <style scoped>
  .footer {
    background-color: #333;
    color: white;
  }
  .footer-content {
    padding: 5px;
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    max-width: 100%;
  }
  .left-column {
    flex-basis: 30%;
    font-weight: bold;
    line-height: 1.5;
    text-align: justify;
    padding: 0 20px;
    margin:5px auto;
    margin-left: 10px;
  }

  .logo {
    max-width: 200px;
    margin: 20px 0;
  }

  .right-column {
    flex-basis: 38%;
    margin: auto;
    padding: 15px;
  }

  .form-group {
    margin-bottom: 15px;
  }

  .form-group label {
    display: block;
    font-weight: bold;
    margin-bottom: 5px;
    text-align: left;
    margin-top: 10px;
  }

  .form-group input,.form-group textarea {
    width: 100%; 
    padding: 10px;
    border: 1px solid #ccc;
  }

  button[type="submit"] {
    background-color: #007BFF;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
  }
  .footer-bottom {
    margin-top: 10px;
    font-size: 12px;
  }
  </style>
  