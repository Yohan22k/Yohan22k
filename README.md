<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multiplica por 2</title>
    <style>
        body {
            background-color: black;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-family: Arial, sans-serif;
            font-size: 6vw; /* Tamaño de fuente responsivo */
        }
        #number {
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div id="number" onclick="multiplyByTwo()">4</div>

    <script>
        function multiplyByTwo() {
            var numberElement = document.getElementById('number');
            var currentNumber = parseInt(numberElement.innerText);
            numberElement.innerText = currentNumber * 2;
        }
    </script>
</body>
</html>
