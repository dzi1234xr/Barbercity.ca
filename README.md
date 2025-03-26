<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Salon Booking</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1 id="title">💇‍♀️ Book Your Salon in Longueuil, QC</h1>

    <label>🌍 Select Language:</label>
    <select id="languageSelect" onchange="changeLanguage()">
        <option value="en">🇬🇧 English</option>
        <option value="fr">🇫🇷 Français</option>
    </select>

    <label>🔍 Choose a city:</label>
    <select id="citySelect" onchange="filterByCity()">
        <option value="Longueuil">Longueuil, QC</option>
        <option value="Montreal">Montreal, QC</option>
    </select>

    <div id="salonList"></div>

    <script src="script.js"></script>
</body>
</html>
