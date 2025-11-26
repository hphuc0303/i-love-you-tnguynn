# i-love-you-tnguynn 
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Làm người yêu tui nha?</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 100px;
        }
        button {
            padding: 10px 20px;
            font-size: 18px;
            margin: 10px;
            cursor: pointer;
        }
        #no {
            position: absolute;
        }
    </style>
</head>
<body>

    <h1>Làm người yêu tui nha? 🥺❤️</h1>

    <button onclick="yes()">Dét dét ❤️</button>
    <button id="no" onmouseover="chay()" ontouchstart="chay()">Say no 😭</button>

    <script>
        function yes() {
            window.location.href = "camon.html";
        }

        function chay() {
            let x = Math.random() * window.innerWidth / 1.3;
            let y = Math.random() * window.innerHeight / 1.3;
            document.getElementById("no").style.left = x + "px";
            document.getElementById("no").style.top = y + "px";
        }
    </script>

</body>
</html>
