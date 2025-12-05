# kms-umkmsususegar
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UMKM Susu Segar</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: #f4f4f4;
        }
        header {
            background: #1976D2;
            padding: 20px;
            color: white;
            text-align: center;
        }
        nav {
            background: #0D47A1;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        .container {
            padding: 30px;
        }
        .produk {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
        }
        .card {
            background: white;
            padding: 20px;
            width: 250px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #0D47A1;
            color: white;
            margin-top: 40px;
        }
    </style>
</head>
<body>

<header>
    <h1>UMKM Susu Segar</h1>
    <p>Kesegaran Asli Dari Peternak Lokal</p>
</header>

<nav>
    <a href="#">Beranda</a>
    <a href="#produk">Produk</a>
    <a href="#kontak">Kontak</a>
</nav>

<div class="container">
    <h2 id="produk">Produk Kami</h2>
    <div class="produk">

        <div class="card">
            <h3>Susu Segar Original</h3>
            <p>Volume: 1 Liter</p>
            <p>Harga: Rp 15.000</p>
        </div>

        <div class="card">
            <h3>Susu Strawberry</h3>
            <p>Volume: 1 Liter</p>
            <p>Harga: Rp 18.000</p>
        </div>

        <div class="card">
            <h3>Susu Coklat</h3>
            <p>Volume: 1 Liter</p>
            <p>Harga: Rp 18.000</p>
        </div>

    </div>
</div>

<footer id="kontak">
    <p>Hubungi kami: 0823-xxx-xxxx</p>
    <p>Alamat: Salatiga</p>
</footer>

</body>
</html>
