<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Farhan Store</title>

<style>
body {
  margin:0;
  font-family: Arial, sans-serif;
  background:#0f172a;
  color:#fff;
}

header {
  background:#020617;
  padding:16px;
  text-align:center;
  font-size:22px;
  font-weight:bold;
}

.container {
  padding:16px;
}

.products {
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(160px,1fr));
  gap:16px;
}

.card {
  background:#020617;
  border-radius:14px;
  padding:14px;
  box-shadow:0 0 20px rgba(34,197,94,0.15);
}

.card h3 {
  font-size:16px;
  margin:6px 0;
}

.price {
  color:#22c55e;
  font-weight:bold;
  margin-bottom:8px;
}

.btn {
  background:#22c55e;
  border:none;
  color:#000;
  padding:10px;
  width:100%;
  border-radius:10px;
  font-weight:bold;
  cursor:pointer;
}

.btn:hover {
  opacity:.85;
}

.cart {
  position:fixed;
  bottom:0;
  left:0;
  right:0;
  background:#020617;
  padding:14px;
  display:flex;
  justify-content:space-between;
  align-items:center;
  box-shadow:0 -4px 20px rgba(0,0,0,.6);
}

.cart span {
  font-weight:bold;
}

.checkout {
  background:#2563eb;
  color:#fff;
  border:none;
  padding:10px 16px;
  border-radius:12px;
  font-weight:bold;
  cursor:pointer;
}
</style>
</head>

<body>

<header>🛒 FARHAN STORE</header>

<div class="container">
  <div class="products">

    <div class="card">
      <h3>Joki FF Rank</h3>
      <div class="price">Rp25.000</div>
      <button class="btn" onclick="addCart(25000)">Tambah</button>
    </div>

    <div class="card">
      <h3>Joki ML Rank</h3>
      <div class="price">Rp30.000</div>
      <button class="btn" onclick="addCart(30000)">Tambah</button>
    </div>

    <div class="card">
      <h3>Room Wangi ML</h3>
      <div class="price">Rp20.000</div>
      <button class="btn" onclick="addCart(20000)">Tambah</button>
    </div>

  </div>
</div>

<div class="cart">
  <span>Total: Rp <span id="total">0</span></span>
  <button class="checkout" onclick="checkout()">Checkout</button>
</div>

<script>
let total = 0;

function addCart(harga){
  total += harga;
  document.getElementById("total").innerText = total.toLocaleString();
}

function checkout(){
  if(total === 0){
    alert("Keranjang masih kosong");
    return;
  }
  window.open(
    "https://wa.me/6285717426626?text=Halo%20Farhan%20Store,%20saya%20mau%20pesan%20dengan%20total%20Rp"+total,
    "_blank"
  );
}
</script>

</body>
</html>
