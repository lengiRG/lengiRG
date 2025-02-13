- <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¿Quieres ser mi San Valentín?</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
            background-color: #ffc0cb;
            font-family: 'Arial', sans-serif;
            text-align: center;
        }
        h1 {
            color: #ff0000;
            font-size: 2.5rem;
        }
        .buttons {
            margin-top: 20px;
            position: relative;
        }
        button {
            font-size: 20px;
            padding: 12px 24px;
            margin: 10px;
            cursor: pointer;
            border: none;
            border-radius: 10px;
            transition: all 0.3s ease;
        }
        #yes {
            background-color: #ff4d4d;
            color: white;
        }
        #no {
            background-color: white;
            color: red;
            position: absolute;
        }
    </style>
</head>
<body>
    <h1>¿Quieres ser mi San Valentín? ❤️</h1>
    <div class="buttons">
        <button id="yes" onclick="yesClick()">Sí 💕</button>
        <button id="no" onmouseover="moveNo()">No 💔</button>
    </div>

    <script>
        function yesClick() {
            window.location.href = "valentin.html";
        }
        
        function moveNo() {
            let button = document.getElementById('no');
            let x = Math.random() * (window.innerWidth - button.offsetWidth);
            let y = Math.random() * (window.innerHeight - button.offsetHeight);
            button.style.left = `${x}px`;
            button.style.top = `${y}px`;
        }
    </script>
</body>
</html>

<!---
lengiRG/lengiRG is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¡Te Amo, Mi Osito! 💖</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
            background-color: #ffb6c1;
            font-family: 'Arial', sans-serif;
            text-align: center;
        }
        h1 {
            color: #ff0000;
            font-size: 3rem;
        }
        p {
            font-size: 1.8rem;
            color: #800000;
        }
        .heart {
            font-size: 4rem;
            animation: heartbeat 1s infinite;
        }
        @keyframes heartbeat {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body>
    <h1>¡Sabía que dirías que sí, mi Carlitos! 💕</h1>
    <p>Te amo muchísimo, mi osito hermoso. Gracias por ser parte de mi vida. 💖</p>
    <p class="heart">❤️❤️❤️</p>
</body>
</html>
