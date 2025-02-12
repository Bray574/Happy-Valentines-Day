<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Für Dich ❤️</title>

    <!-- Google Fonts einbinden -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

    <style>
        /* Allgemeiner Stil */
        body {
            background: linear-gradient(135deg, #f6d7b9, #ffe6e6); /* Sanfter Farbverlauf als Hintergrund */
            font-family: 'Poppins', sans-serif; /* Google Font */
            padding: 20px;
            margin: 0;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        h1 {
            color: #ff4d4d;
            font-size: 36px;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
            animation: fadeInUp 2s ease-out;
        }

        p {
            font-size: 20px;
            color: #333;
            animation: fadeInUp 3s ease-out;
            margin: 10px 0;
        }

        .heart {
            font-size: 60px;
            animation: heartbeat 1s infinite;
            margin-top: 10px;
        }

        .gif-container {
            margin-top: 30px;
            transition: transform 0.3s ease;
        }

        .gif-container:hover {
            transform: scale(1.1); /* Vergrößert das Bild bei Hover */
        }

        .gif-container img {
            width: 220px;
            border-radius: 15px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
        }

        /* Animationen */
        @keyframes heartbeat {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Responsive Design für kleinere Bildschirme */
        @media screen and (max-width: 600px) {
            body {
                padding: 10px;
            }

            h1 {
                font-size: 28px;
            }

            p {
                font-size: 16px;
            }

            .gif-container img {
                width: 180px;
            }

            .heart {
                font-size: 50px;
            }
        }

        @media screen and (max-width: 1024px) {
            h1 {
                font-size: 32px;
            }

            p {
                font-size: 18px;
            }

            .gif-container img {
                width: 200px;
            }

            .heart {
                font-size: 55px;
            }
        }
    </style>
</head>
<body>
    <h1>Für d'Frau mit em herzige Dutt!</h1>
    
    <p> The best people come unexpectedly..</p>
    <p> You were like a shot of espresso, energetic, enthusiastic with a sweet smile.🌟</p>
    <p> Have a nice Valentines Day, Melissa </p>
    <p> Best regards Brayniel </p>
    
    <p> class="heart">💖</p>

    <div class="gif-container">
        <img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExaTViczVvdXdiZDZ4aWx4N3djbGk4MmkyazZ1amNzdGZkbG04MnJ1cCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/b4UHeUnzarvUnjl0fg/giphy.gif" alt="Cute Love Gif">
    </div>

    <audio controls autoplay loop>
        <source src="https://www.bensound.com/bensound-music/bensound-romantic.mp3" type="audio/mp3">
        Dein Browser unterstützt keine Audio-Wiedergabe.
    </audio>
</body>
</html>
