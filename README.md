<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gra w zgadywanie liczb</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Zgadnij liczbę!</h1>
        <p>Wybierz liczbę od 1 do 100:</p>
        <input type="number" id="guessInput" min="1" max="100">
        <button onclick="checkGuess()">Zgadnij</button>
        <p id="resultMessage"></p>
    </div>
    <script src="script.js"></script>
</body>
</html>

