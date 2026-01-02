<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>RHN CAPITAL</title>

<style>
body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: #0b1220;
  color: #eaeaea;
}

/* ===== HERO ===== */
.hero {
  padding: 60px 20px;
  text-align: center;
  background: linear-gradient(135deg,#0b1220,#101b3a);
}

.hero img {
  width: 180px;
  margin-bottom: 20px;
}

.hero h1 {
  color: #f4c26b;
  letter-spacing: 2px;
}

.hero p {
  max-width: 600px;
  margin: auto;
  color: #b8c1ff;
}

/* ===== SECTION ===== */
.section {
  padding: 50px 20px;
  max-width: 1000px;
  margin: auto;
}

.section h2 {
  color: #f4c26b;
  margin-bottom: 20px;
}

/* ===== PORTFOLIO ===== */
.portfolio {
  background: #101b3a;
  padding: 30px;
  border-radius: 12px;
  text-align: center;
}

.portfolio img {
  width: 120px;
  margin: 20px 0;
}

/* ===== GRID ===== */
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
  gap: 20px;
}

.card {
  background: #101b3a;
  padding: 20px;
  border-radius: 12px;
}

/* ===== BUTTON ===== */
.btn {
  display: inline-block;
  padding: 14px 24px;
  background: #f4c26b;
  color: #0b1220;
  text-decoration: none;
  font-weight: bold;
  border-radius: 8px;
  margin-top: 15px;
}

.btn:hover {
  background: #ffd98e;
}

/* ===== CONTACT ===== */
.contact a {
  display: block;
  margin: 10px 0;
  padding: 14px;
  background: #101b3a;
  border-radius: 8px;
  color: #fff;
  text-decoration: none;
  font-weight: 500;
}

/* ===== FOOTER ===== */
footer {
  text-align: center;
  padding: 20px;
  background: #060a16;
  color: #777;
}
</style>
</head>

<body>

<!-- HERO -->
<section class="hero">
  <img src="LOGO_RHN.png" alt="RHN Capital">
  <h1>RHN CAPITAL</h1>
  <p>Perusahaan independen yang berfokus pada pengelolaan aset digital dan keuangan masa depan berbasis teknologi.</p>
</section>

<!-- ABOUT -->
<section class="section">
  <h2>Tentang Kami</h2>
  <p>
    RHN Capital dikelola oleh individu muda yang disiplin, berani mengambil keputusan,
    dan berfokus pada pertumbuhan aset digital jangka panjang berbasis blockchain.
  </p>
</section>

<!-- PORTFOLIO -->
<section class="section">
  <h2>Portofolio</h2>
  <div class="portfolio">
    <h3>Bitcoin (BTC)</h3>
    <img src="https://assets.coingecko.com/coins/images/1/large/bitcoin.png">
    <p>Alokasi: <strong>100%</strong></p>
    <a href="https://www.coingecko.com/en/coins/bitcoin" target="_blank" class="btn">
      Lihat di CoinGecko
    </a>
  </div>
</section>

<!-- VISION & MISSION -->
<section class="section">
  <h2>Visi & Misi</h2>
  <div class="grid">
    <div class="card">
      <h4>Visi</h4>
      <p>Menjadi entitas mandiri yang sukses dalam pengelolaan aset digital modern.</p>
    </div>
    <div class="card">
      <h4>Misi</h4>
      <p>Mengelola dana secara bertanggung jawab dan mengedukasi generasi muda.</p>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section class="section contact">
  <h2>Kontak</h2>
  <a href="https://wa.me/6285717826626">📞 WhatsApp</a>
  <a href="https://instagram.com/huyrehan">📸 Instagram</a>
  <a href="ANALISA.html" class="btn">➡ ANALISA RHN CAPITAL</a>
</section>

<footer>
© 2025 RHN Capital. All rights reserved.
</footer>

</body>
</html>
