<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> algo especial para ti </title>
    <style>
        /* Estilos generales */
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            background: linear-gradient(to bottom, #0f0c29, #302b63, #24243e);
            font-family: 'Playfair Display', serif;
            text-align: center;
            overflow: hidden;
            color: #e0e0e0;
        }

        /* Botón */
        .open-flower-btn {
            background: #444;
            border: 3px solid #555;
            padding: 15px 30px;
            border-radius: 25px;
            font-size: 20px;
            font-weight: bold;
            cursor: pointer;
            transition: 0.3s;
            color: #e0e0e0;
        }

        .open-flower-btn:hover {
            background: #222;
            border-color: #777;
            transform: scale(1.2);
        }

        /* Contenedor de la flor */
        .flower-container {
            position: relative;
            width: 150px;
            height: 200px;
            display: flex;
            justify-content: center;
            align-items: center;
            transform: scale(0);
            transition: transform 1s ease-in-out;
        }

        /* Pétalos */
        .petal {
            position: absolute;
            width: 30px;
            height: 80px;
            background: radial-gradient(circle, #ff4b2b, #ff6f61);
            border-radius: 50% 50% 0 0;
            opacity: 0;
            transition: all 1s ease-in-out;
        }

        .petal:nth-child(1) {
            transform: rotate(-45deg) translateY(-40px);
        }

        .petal:nth-child(2) {
            transform: rotate(-15deg) translateY(-40px);
        }

        .petal:nth-child(3) {
            transform: rotate(15deg) translateY(-40px);
        }

        .petal:nth-child(4) {
            transform: rotate(45deg) translateY(-40px);
        }

        /* Centro de la flor */
        .center {
            width: 40px;
            height: 40px;
            background: #ffeb3b;
            border-radius: 50%;
            position: absolute;
            opacity: 0;
            transition: opacity 1s ease-in-out;
        }

        /* Fondo con nombre y corazón */
        .background-text {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 100px;
            color: rgba(255, 255, 255, 0.1);
            z-index: -1;
        }

        /* Mensaje animado */
        .message {
            font-size: 24px;
            color: #e0e0e0;
            font-weight: bold;
            opacity: 0;
            transition: opacity 1s ease-in-out;
            margin-top: 40px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }

        /* Corazones de lluvia */
        .falling-heart {
            position: absolute;
            width: 25px;
            height: 25px;
            background-color: red;
            clip-path: polygon(50% 0%, 0% 50%, 100% 50%);
            animation: fall 7s infinite;
            opacity: 0;
        }

        .falling-heart::before,
        .falling-heart::after {
            content: '';
            position: absolute;
            width: 25px;
            height: 25px;
            background-color: red;
            border-radius: 50%;
            top: 0;
        }

        .falling-heart::before {
            left: -12.5px;
        }

        .falling-heart::after {
            left: 12.5px;
        }

        @keyframes fall {
            0% {
                top: -100px;
                opacity: 1;
                transform: rotateZ(0deg);
            }

            100% {
                top: 100vh;
                opacity: 0;
                transform: rotateZ(360deg);
            }
        }

        /* Luna */
        .moon {
            position: absolute;
            top: 20px;
            right: 20px;
            width: 100px;
            height: 100px;
            background: radial-gradient(circle, #fff, #bbb);
            border-radius: 50%;
            box-shadow: 0 0 15px rgba(255, 255, 255, 0.5);
        }
    </style>
</head>

<body>

    <div class="background-text">Evelincita 💖</div>

    <h1 style="color: #e0e0e0; text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.7);">🌹 algo especial para ti, mi linda 🌹
    </h1>

    <!-- Botón para abrir la flor -->
    <button class="open-flower-btn" id="openButton" onclick="bloomFlower()">✨ Haz clic aquí ✨</button>

    <!-- Contenedor de la flor -->
    <div class="flower-container" id="flower">
        <div class="petal"></div>
        <div class="petal"></div>
        <div class="petal"></div>
        <div class="petal"></div>
        <div class="center"></div>
    </div>

    <!-- Luna -->
    <div class="moon"></div>

    <!-- Mensaje sorpresa -->
    <p class="message" id="message"></p>

    <script>
        function bloomFlower() {
            document.getElementById("openButton").style.display = "none";
            let flower = document.getElementById("flower");
            let petals = document.querySelectorAll(".petal");
            let center = document.querySelector(".center");
            let message = document.getElementById("message");

            flower.style.transform = "scale(1)";

            // Mostrar pétalos con retraso
            petals.forEach((petal, index) => {
                setTimeout(() => {
                    petal.style.opacity = "1";
                }, index * 500);
            });

            // Mostrar centro y mensaje después de los pétalos
            setTimeout(() => {
                center.style.opacity = "1";
                message.style.opacity = "1";
                typeMessage();
                createFallingHearts();
            }, 2500);
        }

        function typeMessage() {
            let messageText = "Eres mi flor más hermosa 🌹 Te quiero, mi linda buenas noches 💖";
            let messageElement = document.getElementById("message");
            let index = 0;
            messageElement.textContent = "";

            function type() {
                if (index < messageText.length) {
                    messageElement.textContent += messageText[index];
                    index++;
                    setTimeout(type, 100);
                }
            }
            type();
        }

        function createFallingHearts() {
            for (let i = 0; i < 50; i++) {
                let heart = document.createElement('div');
                heart.classList.add('falling-heart');
                heart.style.left = Math.random() * 100 + 'vw';
                heart.style.animationDuration = Math.random() * 2 + 3 + 's';
                heart.style.animationDelay = Math.random() * 5 + 's';
                document.body.appendChild(heart);
            }
        }
    </script>

</body>

</html>
