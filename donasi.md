<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Donasi untuk Aplikasi Cek Eligible PISN</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <script src="bootstrap.bundle.min.js"></script>
    <script src="navbar.js"></script>
    <style>
        body {
            font-family: 'Segoe UI', sans-serif;
            background-color: #f8f9fa;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }
        .navbar { box-shadow: 0px 4px 6px rgba(0,0,0,0.1); }
        .dropdown-menu a { transition: background-color 0.2s ease; }
        .dropdown-menu a:hover { background-color: #f1f1f1; }
        .container { animation: fadeIn 0.5s ease-in-out; flex: 1; }
        @keyframes fadeIn { from {opacity:0; transform: translateY(10px);} to {opacity:1; transform: translateY(0);} }
        footer {
            background-color: #ffffff;
            padding: 10px 0;
            box-shadow: 0px -2px 5px rgba(0,0,0,0.05);
            text-align: center;
            font-size: 14px;
        }
        footer a { color: #0d6efd; text-decoration: none; }
        footer a:hover { text-decoration: underline; }
    </style>
</head>
<body>

<!-- Navbar -->
<div id="navbar-container"></div>

<!-- Content -->
<div class="container my-4">
    <h1>Donasi untuk Aplikasi Cek Eligible PISN</h1>

    <p>
        Aplikasi ini membantu kampus mengecek kelayakan mahasiswa PISN dengan cepat. 
        Jika Anda merasa terbantu, Anda dapat berdonasi agar pengembangan dan biaya server tetap berjalan.
    </p>
    <p>
        Nominal bebas—kecil atau besar, semuanya sangat berarti. Terima kasih atas dukungannya.
    </p>

    <h3>Metode Donasi</h3>
    <ul>
        <li>E-Wallet (OVO/GoPay/DANA): <strong>0812-1718-1715</strong> (Alan Budi Kusuma)</li>
        <li>Transfer Bank BSI: <strong>1043-187-957</strong> a.n. <strong>Alan Budi Kusuma</strong></li>
    </ul>

    <hr class="my-4">

    <p>Halaman <a href="aktivasi.html">Aktivasi</a></p>
    <p>Generate Kode Aktivasi: <a href="https://tanyabot.my.id/PISN-Checker/aktivasi.php" target="_blank" rel="noopener">Klik di sini</a></p>
</div>

<!-- Footer -->
<footer>
    <div class="container">
        &copy; 2025 Cek Eligible PISN — Open Source on 
        <a href="https://github.com/masbudikusuma/PISN_Checker" target="_blank" rel="noopener">GitHub</a>
    </div>
</footer>

</body>
</html>
