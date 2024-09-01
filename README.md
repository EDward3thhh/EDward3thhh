<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Position Calculator</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Position Calculator</h1>

        <div class="language-selector">
            <button id="english-btn">English</button>
            <button id="thai-btn">ไทย</button>
        </div>

        <div class="form">
            <label for="loss">Loss ($) </label>
            <input type="number" id="loss" placeholder="Enter loss in USD">

            <label for="sl-percentage">SL (%) </label>
            <input type="number" id="sl-percentage" placeholder="Enter Stop Loss percentage">

            <label for="leverage">Leverage </label>
            <input type="number" id="leverage" placeholder="Enter Leverage">

            <button id="calculate-btn">Calculate</button>
        </div>

        <div class="result">
            <p id="position-result">Position: </p>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
