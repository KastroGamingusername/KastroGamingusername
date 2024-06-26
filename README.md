<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gra w klikanie</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Gra w klikanie</h1>
        <p>Kliknij w przycisk 100 000 razy!</p>
        <button id="clickButton" onclick="incrementCounter()">Kliknij mnie!</button>
        <p>Liczba kliknięć: <span id="clickCount">0</span></p>
        <p id="resultMessage"></p>
    </div>
    <script src="script.js"></script>
</body>
</html>
