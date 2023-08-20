<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Website Pribadi</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.5.2/dist/css/bootstrap.min.css">
  <style>
    /* Gaya umum untuk halaman */
    body {
      font-family: Arial, sans-serif;
      background-color: #f8f9fa;
      padding-top: 60px;
    }

    header {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      background-color: #343a40;
      padding: 10px 0;
      z-index: 100;
      animation: slide-down 0.5s ease;
    }

    @keyframes slide-down {
      from {
        transform: translateY(-100%);
      }
      to {
        transform: translateY(0);
      }
    }

    nav ul {
      list-style-type: none;
      display: flex;
      margin: 0;
      padding: 0;
    }
    
    nav ul li {
      margin-right: 20px;
    }

    /* Gaya untuk konten */
    section {
      padding: 40px 0;
    }

    h1, h2, h3 {
      color: #343a40;
    }

    /* Gaya tombol */
    .btn-custom {
      background-color: #343a40;
      color: #fff;
      border: none;
      transition: background-color 0.3s ease;
    }

    .btn-custom:hover {
      background-color: #212529;
    }

    /* Animasi muncul */
    .fade-in {
      opacity: 0;
      transform: translateY(20px);
      animation: fade-in 0.5s forwards;
    }

    @keyframes fade-in {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#beranda">Beranda</a></li>
        <li><a href="#portofolio">Portofolio</a></li>
        <li><a href="#informasi">Informasi Diri</a></li>
        <li><a href="#kontak">Kontak</a></li>
      </ul>
    </nav>
  </header>
  
  <section id="beranda">
    <div class="container text-center fade-in">
      <h1>Selamat Datang di Website Saya</h1>
      <p>Ini adalah halaman beranda dari website pribadi saya.</p>
      <a href="#kontak" class="btn btn-custom">Hubungi Saya</a>
    </div>
  </section>

  <!-- Tambahkan bagian portofolio, informasi diri, dan kontak sesuai kebutuhan -->

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.5.2/dist/js/bootstrap.bundle.min.js"></script>
  <script>
    // Skrip JavaScript jika diperlukan
  </script>
</body>
</html>
