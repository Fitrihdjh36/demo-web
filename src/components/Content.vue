<template>
    <div class="content">
      <div class="question">Tentang Kami</div>
      <div class="judul">INSPIRAZI DESIGN merupakan penyedia layanan Jasa Desain Grafis, Kartu Nama, Brosur, Poster, Flyer, Curicullum Vitae, Kalender, Banner, Kartu Ucapan, Desain undangan dan Stationery dengan harga terjangkau, cepat, bergaransi dan telah dipercayai oleh ratusan klien besar.</div>
      <a href="https://api.whatsapp.com/send?phone=6289679531473" target="_blank">
        <button class="cta-button">Konsultasikan Sekarang</button>
    </a>
      <div class="boxes">
        <!-- Kotak Pertama -->
          <div class="box">
            <img src="@/assets/icon1.png" alt="icon 1" class="icon">
            <p>Tim yang berpengalaman dan kreatif</p>
          </div>
          
          <!-- Kotak Kedua -->
          <div class="box">
            <img src="@/assets/icon2.png" alt="icon 2" class="icon">
            <p>CS yang responsif dan siap membantu</p>
          </div>

          <!-- Kotak Ketiga -->
          <div class="box">
            <img src="@/assets/icon3.png" alt="icon 3" class="icon">
            <p>Layanan terbaik dan tepak waktu</p>
          </div>

          <!-- Kotak Keempat -->
          <div class="box">
            <img src="@/assets/icon4.png" alt="icon 4" class="icon">
            <p>File desain disimpan dalam cloud storage</p>
          </div>
        </div>
      <div class="question">Layanan Kami</div>
        <div class="service-boxes">
          <div class="service-box">
            <img src="@/assets/flayer.png" alt="Desain" class="service-icon">
            <p>Desain Flayer</p>
            <button class="service-btn">Lihat Hasil</button>
          </div>
          <div class="service-box">
            <img src="@/assets/brosur.png" alt="Desain " class="service-icon">
            <p>Desain Brosur</p>
            <button class="service-btn">Lihat Hasil</button>
          </div>
          <div class="service-box">
            <img src="@/assets/cv.png" alt="Desain " class="service-icon">
            <p>Desain CV</p>
            <button class="service-btn">Lihat Hasil</button>
          </div>
          <div class="service-box">
            <img src="@/assets/banner.png" alt="Desain " class="service-icon">
            <p>Desain Banner</p>
            <button class="service-btn">Lihat Hasil</button>
          </div>
          <div class="service-box">
            <img src="@/assets/namecard.png" alt="Desain " class="service-icon">
            <p>Desain Kartu Nama</p>
            <button class="service-btn">Lihat Hasil</button>
          </div>
          <div class="service-box">
            <img src="@/assets/kaos.png" alt="Desain " class="service-icon">
            <p>Desain Kaos & Jersey</p>
            <button class="service-btn">Lihat Hasil</button>
          </div>
          <div class="service-box">
            <img src="@/assets/undangan.png" alt="Desain " class="service-icon">
            <p>Desain Undangan</p>
            <button class="service-btn">Lihat Hasil</button>
          </div>
          <div class="service-box">
            <img src="@/assets/x-banner.png" alt="Desain " class="service-icon">
            <p>Desain X-Banner</p>
            <button class="service-btn">Lihat Hasil</button>
          </div>
        </div>
      <div class="question">Dan semua kebutuhan desain grafis Lainnya...</div>
      <div class="konten">
        <div class="konten-box">
          <img src="@/assets/marketing.png" alt="konten" class="konten-icon">
          <p>Konten Marketing</p>
          <button class="konten-btn">Selengkapnya</button>
        </div>
        <div class="konten-box">
          <img src="@/assets/branding.png" alt="konten " class="konten-icon">
          <p>Konten Branding</p>
          <button class="konten-btn">Selengkapnya</button>
        </div>
        <div class="konten-box">
          <img src="@/assets/ig.png" alt="konten " class="konten-icon">
          <p>Konten Instagram</p>
          <button class="konten-btn">Selengkapnya</button>
        </div>
      </div>
    </div>
  </template>
   
  <script> 
export default {
  name: 'AppContent',
}
  </script>
  
  <style scoped>
  .content {
    padding: 20px;
  }
  .judul{
    font-size: 18px;
    line-height: 2;
  }
  .cta-button {
    margin: 40px auto 100px;
    background-color: rgb(2, 116, 197);
    color: white;
    padding: 10px;
    border-radius: 5px;
    border: none;
    cursor: pointer;
    transition: box-shadow 0.3s ease;
  }
  .cta-button:hover {
    box-shadow: 0px 6px 10px rgba(0, 0, 0, 0.2);
  }
  .cta-button:active {
    box-shadow: inset 4px rgba(0, 0, 0, 0.5);
  }
  .question {
    margin: 20px auto;
    font-size: 25px;
    font-weight: bold;
    color: rgb(26, 93, 174);
  }
  .boxes {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin-bottom: 100px;
  }
  .box {
    width: 250px;
    height: 280px;
    background-color: rgb(39, 115, 208);
    margin: 50px 20px;
    box-sizing: border-box;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    border-radius: 15px;
    color: white;
  }
  .icon {
    width: 130px; 
    height: 130px;
    margin-bottom: 30px;
  }
  .service-boxes {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin-bottom: 80px;
  }
  .service-icon {
    margin: 10px 25px;
    width: 220px;
    height: 220px;
    margin-bottom: 5px;
    border-radius: 10px;
  }
  .service-btn {
    background-color: #007BFF;
    color: white;
    padding: 10px 80px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    margin-bottom: 30px;
  }
  .konten {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin-bottom: 100px;
  }
  .konten-box, p {
    margin: 5px 0 10px;
    font-weight: bold;
  }
  .konten-icon {
    max-width: 350px;
    margin: 10px;
    margin-bottom: 5px;
  }
  .konten-btn {
    background-color: #007BFF;
    color: white;
    padding: 10px 100px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    margin-bottom: 15px;
  }

  </style>