ada-kirtasiye/
│
├── index.html
├── hakkimizda.html
├── urunler.html
├── iletisim.html
└── style.css
<!DOCTYPE html>
<html lang=“tr”>
<head>
  <meta charset=“UTF-8”>
  <title>Ada Kırtasiye</title>
  <link rel=“stylesheet” href=“style.css”>
</head>
<body>
  <header>
    <h1>Ada Kırtasiye</h1>
  </header>

  <nav>
    <ul>
      <li><a href=“index.html”>Ana Sayfa</a></li>
      <li><a href=“urunler.html”>Ürünler</a></li>
      <li><a href=“hakkimizda.html”>Hakkımızda</a></li>
      <li><a href=“iletisim.html”>İletişim</a></li>
    </ul>
  </nav>

  <main>
    <h2>Hoş Geldiniz!</h2>
    <p>Kitap, defter, kalem ve YooHoo dostlarımız burada sizi bekliyor.</p>
    <img src=“yoohoo.png” alt=“YooHoo Figürü” width=“200”>
  </main>

  <footer>
    © 2025 Ada Kırtasiye – Tüm hakları saklıdır.
  </footer>
</body>
</html>

body {
  font-family: Arial, sans-serif;
  background-color: #fff8e1;
  color: #000;
  margin: 0;
  padding: 0;
}

header {
  background-color: red;
  color: white;
  padding: 20px;
  text-align: center;
}

nav ul {
  background-color: black;
  list-style: none;
  padding: 10px;
  display: flex;
  justify-content: center;
}

nav ul li {
  margin: 0 15px;
}

nav ul li a {
  color: yellow;
  text-decoration: none;
  font-weight: bold;
}

main {
  padding: 20px;
  text-align: center;
}

footer {
  background-color: black;
  color: red;
  text-align: center;
  padding: 10px;
  position: fixed;
  width: 100%;
  bottom: 0;
}
<main>
  <h2>Ürünlerimiz</h2>
  <ul>
    <li>Renkli Defter - 35₺</li>
    <li>Kalem Seti - 25₺</li>
    <li>YooHoo Figürü (Sınırlı) - 60₺</li>
    <li>Boyama Kitabı - 40₺</li>
  </ul>
</main>
<main>
  <h2>İletişim</h2>
  <form>
    <label>Adınız:</label><br>
    <input type=“text”><br>
    <label>E-posta:</label><br>
    <input type=“email”><br>
    <label>Mesaj:</label><br>
    <textarea rows=“5”></textarea><br>
    <button type=“submit”>Gönder</button>
  </form>
</main>
