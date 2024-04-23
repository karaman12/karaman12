<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Ticaret Sitesi</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <img src="sol_resim.jpg" alt="Sol Resim">
            <img src="sag_resim.jpg" alt="Sağ Resim">
        </div>
    </header>
    <main>
        <div class="container">
            <div class="product-images">
                <img src="kucuk_resim1.jpg" alt="Ürün 1">
                <img src="kucuk_resim2.jpg" alt="Ürün 2">
                <img src="kucuk_resim3.jpg" alt="Ürün 3">
                <!-- Diğer küçük resimler buraya eklenecek -->
            </div>
        </div>
    </main>
    <footer>
        <p>&copy; 2024 Bu siteyi tasarlayan Ahmet Ertekin. Bütün telif hakları ona aittir.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
}

header {
    display: flex;
    justify-content: space-between;
    padding: 20px 0;
    background-color: #f1f1f1;
}

header img {
    max-width: 45%;
}

main {
    padding: 20px 0;
}

.product-images {
    display: flex;
    justify-content: center;
    gap: 20px;
}

.product-images img {
    width: 100px;
    height: 100px;
    border: 2px solid #ccc;
}

footer {
    text-align: center;
    background-color: #333;
    color: #fff;
    padding: 20px 0;
}

