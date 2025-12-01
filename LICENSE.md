<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Avtomobil Ijarasi Tizimi</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>🚗 Avtomobil Ijarasi Tizimi</h1>
</header>

<section class="form-section">
    <h2>Avtomobil tanlang va ijara muddati kiriting</h2>

    <label>Avtomobil:</label>
    <select id="car">
        <option value="350000">Gentra - 350 000 so'm/kun</option>
        <option value="550000">Malibu 2 - 550 000 so'm/kun</option>
        <option value="800000">Tracker - 800 000 so'm/kun</option>
    </select>

    <label>Necha kunga ijaraga olasiz?</label>
    <input type="number" id="days" placeholder="Kun soni">

    <button onclick="Hisobla()">💰 Narxni hisoblash</button>

    <h3 id="result"></h3>
</section>

<script src="script.js"></script>
</body>
</html>
