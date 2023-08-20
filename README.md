<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Website Pribadi</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.5.2/dist/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">
  <style>
    /* ... Gaya umum dan CSS sebelumnya ... */

    /* Animasi muncul dengan efek "bounceIn" */
    .bounce-in {
      opacity: 0;
      transform: translateY(20px);
      animation: bounce-in 1s forwards;
    }

    @keyframes bounce-in {
      0% {
        opacity: 0;
        transform: translateY(20px);
      }
      70% {
        transform: translateY(-10px);
      }
      100% {
        opacity: 1;
        transform: translateY(0);
      }
    }

    /* Animasi berputar "spin" */
    .spin {
      animation: spin 2s linear infinite;
    }

    @keyframes spin {
      0% {
        transform: rotate(0deg);
      }
      100% {
        transform: rotate(360deg);
      }
    }
  </style>
</head>
<body>
  <!-- ... Bagian header dan konten sebelumnya ... -->
  
  <section id="portofolio">
    <div class="container text-center fade-in animate__animated animate__fadeInUp">
      <h2>Portofolio</h2>
      <div class="row">
        <div class="col-md-4 mb-4">
          <div class="card bounce-in">
            <div class="card-body">
              <h4 class="card-title">Proyek A</h4>
              <p class="card-text">Deskripsi proyek A.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-4">
          <div class="card bounce-in">
            <div class="card-body">
              <h4 class="card-title">Proyek B</h4>
              <p class="card-text">Deskripsi proyek B.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-4">
          <div class="card bounce-in">
            <div class="card-body">
              <h4 class="card-title">Proyek C</h4>
              <p class="card-text">Deskripsi proyek C.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ... Bagian informasi diri dan kontak sebelumnya ... -->

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.5.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
