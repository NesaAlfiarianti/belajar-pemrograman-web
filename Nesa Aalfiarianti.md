# belajar-pemrograman-web
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Selamat Datang</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #93c5fd, #e0f2fe);
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      animation: fadeIn 1.2s ease;
    }

    .container {
      background: white;
      padding: 50px;
      border-radius: 20px;
      box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
      text-align: center;
      max-width: 500px;
      width: 100%;
    }

    h1 {
      font-size: 36px;
      color: #1e3a8a;
      margin-bottom: 10px;
    }

    p {
      font-size: 18px;
      color: #374151;
      margin-bottom: 30px;
    }

    a.button {
      display: inline-block;
      padding: 12px 28px;
      background: #2563eb;
      color: white;
      border-radius: 10px;
      font-size: 16px;
      text-decoration: none;
      transition: all 0.3s ease;
    }

    a.button:hover {
      background: #1d4ed8;
      transform: scale(1.05);
    }

    .logo {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 20px;
      border: 4px solid #93c5fd;
    }

     fadeIn {
      from {
        opacity: 0;
        transform: translateY(30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <img src="foto saya .jpg" alt="Foto Nesa" class="logo" />
    <h1>Halo, Selamat Datang!</h1>
    <p>Ini adalah halaman utama situs pribadi saya <strong>NESA</strong>. Silakan klik tombol di bawah untuk mengenal saya lebih jauh.</p>
    <a href="Profil.html" class="button">Lihat Profil Saya</a>
  </div>
</body>
</html>
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Profil Nesa Alfiarianti</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(to right, #a0c4ff, #bde0fe);
      margin: 0;
      padding: 0;
      color: #1e3a5f;
    }

    .container {
      max-width: 800px;
      margin: 40px auto;
      padding: 30px;
      background: #ffffff;
      border-radius: 16px;
      box-shadow: 0 8px 25px rgba(0, 0, 0, 0.1);
    }

    header {
      text-align: center;
    }

    header img {
      width: 150px;
      height: 150px;
      object-fit: cover;
      border-radius: 50%;
      border: 4px solid #90cdf4;
      margin-bottom: 15px;
    }

    h1 {
      font-size: 28px;
      color: #1e3a8a;
      margin-bottom: 5px;
    }

    .tagline {
      font-style: italic;
      color: #475569;
    }

    section {
      margin-top: 30px;
    }

    h2 {
      font-size: 22px;
      border-bottom: 2px solid #dbeafe;
      padding-bottom: 6px;
      margin-bottom: 15px;
      color: #1e40af;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    li {
      margin-bottom: 10px;
    }

    strong {
      display: inline-block;
      width: 100px;
      font-weight: 600;
    }

    .about p {
      line-height: 1.8;
      text-align: justify;
    }

    .contact-info a {
      color: #2563eb;
      text-decoration: none;
    }

    .contact-info a:hover {
      text-decoration: underline;
    }

    footer {
      text-align: center;
      margin-top: 40px;
      font-size: 14px;
      color: #64748b;
    }

    .button {
      display: inline-block;
      margin-top: 15px;
      padding: 10px 20px;
      background-color: #3b82f6;
      color: white;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      transition: background-color 0.3s ease;
    }

    .button:hover {
      background-color: #2563eb;
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <img src="foto saya .jpg" alt="Foto Nesa" />
      <h1>Nesa Alfiarianti</h1>
      <p class="tagline">Mahasiswa Universitas Sulawesi Barat</p>
    </header>

    <section class="biodata">
      <h2>Biodata</h2>
      <ul>
        <li><strong>Nama:</strong> Nesa Alfiarianti</li>
        <li><strong>Usia:</strong> 18 Tahun</li>
        <li><strong>Alamat:</strong> Mamasa, Sulawesi Barat</li>
        <li><strong>Moto:</strong> Temukan keindahan, jadilah dirimu sendiri</li>
      </ul>
    </section>

    <section class="about">
      <h2>Tentang Saya</h2>
      <p>
        Saya adalah pribadi yang tenang dan lebih nyaman dalam kesunyian dari pada keramaian. Musik menjadi tempat saya pulang, tempat saya meresapi dunia dan diri sendiri. Saya tidak banyak bicara, bukan karena tak peduli, tapi karena saya lebih suka meresapi dari pada bereaksi. Dulu saya sangat pemalu, bahkan untuk sekadar menyapa saja butuh keberanian besar. Namun waktu mengajarkan bahwa menjadi diri sendiri adalah hal terbaik yang bisa saya lakukan. Saya pencinta kopi, pengamat film, dan teman ngobrol yang menyenangkan jika sudah saling mengenal. Saya mungkin pendiam, tapi saya hadir sepenuhnya.
      </p>
    </section>

    <section class="contact-info">
      <h2>Kontak</h2>
      <p>Email: <a href="mailto:12790eca@gmail.com">12790eca@gmail.com</a></p>
      <p>Telepon: 0823-3542-8258</p>
      <p>Instagram: <a href="https://instagram.com/nesa_alfiarianti" target="_blank">@nesa_alfiarianti</a></p>
    </section>

    <footer>
      &copy; 2025 Nesa Alfiarianti. Semua Hak Dilindungi. <br />
      <a href="countact.html" class="button">Kontak</a>
    </footer>
  </div>
</body>
</html>
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Kontak Saya</title>
  <link rel="stylesheet" href="{{ url_for('static', filename='style.css') }}" />
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f0f4f8;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 500px;
      margin: 60px auto;
      background-color: #ffffff;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
    }
    h2 {
      text-align: center;
      color: #333;
      margin-bottom: 25px;
    }
    label {
      display: block;
      margin: 12px 0 5px;
      color: #555;
      font-weight: 500;
    }
    input[type="text"],
    input[type="email"],
    textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 14px;
      box-sizing: border-box;
    }
    textarea {
      resize: vertical;
    }
    button {
      width: 100%;
      padding: 12px;
      background-color: #007bff;
      color: white;
      border: none;
      border-radius: 6px;
      font-size: 16px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }
    button:hover {
      background-color: #0056b3;
    }
    a {
      display: block;
      text-align: center;
      margin-top: 20px;
      text-decoration: none;
      color: #007bff;
    }
    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="container">
    <h2>Hubungi Saya</h2>
    <form method="POST">
      <label for="name">Nama:</label>
      <input type="text" id="name" name="name" required />

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required />

      <label for="message">Kirimkan saya Pesan:</label>
      <textarea id="message" name="message" rows="5" required></textarea>

      <button type="submit">Kirim</button>
    </form>
    <a href="Profil.html" class="button">← Kembali ke Beranda</a>
  </div>
</body>
</html>
