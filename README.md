<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>⚡ BerMatModZ ⚡ - Perfil Hacker</title>
    <style>
        /* Fondo oscuro estilo hacker */
        body {
            font-family: "Courier New", Courier, monospace;
            background-color: #121212;
            color: #00FF00;
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            overflow: hidden;
        }

        /* Animación de parpadeo en texto */
        h1, h2, p {
            font-size: 3em;
            animation: blink 1.5s infinite;
        }

        @keyframes blink {
            50% {
                opacity: 0;
            }
        }

        /* Estilo para enlaces de redes sociales */
        .social-links a {
            color: #00FF00;
            text-decoration: none;
            font-size: 1.5em;
            margin: 10px;
            display: inline-block;
            transition: 0.3s;
            border: 2px solid #00FF00;
            padding: 10px;
            border-radius: 5px;
        }

        .social-links a:hover {
            color: #FF0000;
            background-color: #00FF00;
            border-color: #FF0000;
            transform: scale(1.1);
        }

        /* Fondo con la máscara de Anonymous */
        .background {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-image: url('https://upload.wikimedia.org/wikipedia/commons/a/a0/Anonymous_mask.svg');
            background-size: cover;
            opacity: 0.1;
            z-index: -1;
        }

        /* Estilo del cuadro de perfil */
        .profile {
            text-align: center;
            border: 3px solid #00FF00;
            padding: 20px;
            border-radius: 10px;
            background-color: rgba(18, 18, 18, 0.8);
            box-shadow: 0px 0px 15px #00FF00;
            animation: pulse 2s infinite;
        }

        /* Animación de pulsación en el cuadro */
        @keyframes pulse {
            0% {
                box-shadow: 0px 0px 15px #00FF00;
            }
            50% {
                box-shadow: 0px 0px 25px #FF0000;
            }
            100% {
                box-shadow: 0px 0px 15px #00FF00;
            }
        }

        .profile img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            margin: 20px;
        }

        .profile-info {
            margin-top: 20px;
            font-size: 1.5em;
            color: #00FF00;
            padding: 15px;
            background-color: rgba(0, 0, 0, 0.7);
            border: 2px solid #00FF00;
            border-radius: 5px;
            animation: fadeIn 3s ease-in-out;
        }

        /* Efecto de desvanecimiento de la información */
        @keyframes fadeIn {
            0% {
                opacity: 0;
            }
            100% {
                opacity: 1;
            }
        }

        /* Estilo de los cuadros de información */
        .info-box {
            padding: 20px;
            margin: 20px;
            border: 2px solid #00FF00;
            background-color: rgba(0, 0, 0, 0.8);
            animation: flash 1s infinite alternate;
            border-radius: 10px;
        }

        /* Efecto de parpadeo en los cuadros */
        @keyframes flash {
            50% {
                background-color: rgba(0, 255, 0, 0.5);
            }
        }

        /* Estilo del banner */
        .banner {
            font-size: 3em;
            color: #FF0000;
            margin-top: 30px;
            animation: rotate 10s linear infinite;
        }

        /* Animación de rotación */
        @keyframes rotate {
            0% {
                transform: rotate(0deg);
            }
            100% {
                transform: rotate(360deg);
            }
        }

        /* Diseño adaptativo para pantallas pequeñas */
        @media (max-width: 600px) {
            h1 {
                font-size: 2.5em;
            }

            h2 {
                font-size: 1.8em;
            }

            .profile-info {
                font-size: 1.2em;
            }

            .social-links a {
                font-size: 1.2em;
                padding: 8px;
            }

            .profile {
                padding: 15px;
            }

            .banner {
                font-size: 2.5em;
            }

            .info-box {
                font-size: 1.2em;
            }

            .profile img {
                width: 120px;
                height: 120px;
            }
        }
    </style>
</head>
<body>
    <div class="background"></div>
    <div class="profile">
        <img src="https://i.pinimg.com/originals/7f/72/19/7f7219f22e9d81e9f6d09d7ec1899b85.jpg" alt="BerMatModZ">
        <h1>⚡ BerMatModZ ⚡</h1>
        <h2>El más temido del ciberespacio</h2>

        <div class="profile-info">
            <p><span>Creador:</span> AnthZz Berrocal</p>
            <p><span>Ubicación:</span> Andahuaylas, Perú</p>
            <p><span>Novia: </span><span style="color: #FF1493;">❤️ Briyidth Jhorgina ❤️</span></p>
            <p><span>Intereses:</span> 💪 Gym, Tecnología, Programación, Ciberseguridad</p>
        </div>

        <div class="info-box">
            <p><span>Redes Sociales:</span></p>
            <div class="social-links">
                <a href="https://www.facebook.com/AnthZzBerrocal" target="_blank">Facebook</a>
                <a href="https://www.instagram.com/AnthZzBerrocal" target="_blank">Instagram</a>
                <a href="https://open.spotify.com/user/AnthZzBerrocal" target="_blank">Spotify</a>
                <a href="https://www.youtube.com/c/AnthZzBerrocal" target="_blank">YouTube</a>
                <a href="https://wa.me/51900233784" target="_blank">WhatsApp</a>
            </div>
        </div>

        <div class="banner">⚡ Anonymous | BerMatModZ ⚡</div>

        <div class="info-box">
            <p>Mi objetivo: Cambiar el mundo a través de la tecnología. Siempre buscando nuevas fronteras para hackear.</p>
        </div>
    </div>
</body>
</html>
