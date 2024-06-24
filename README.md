<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>كؤوس الماء</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <div class="cup" id="cup1">
            <div class="water" id="water1"></div>
        </div>
        <div class="cup" id="cup2">
            <div class="water" id="water2"></div>
        </div>
    </div>
    <div class="controls">
        <button onclick="addPoints(1, 10)">إضافة 10 نقاط إلى الكأس 1</button>
        <button onclick="addPoints(2, 20)">إضافة 20 نقطة إلى الكأس 2</button>
    </div>
    <script src="script.js"></script>
</body>
</html>
