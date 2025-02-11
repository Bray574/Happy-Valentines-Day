<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Für Dich ❤️</title>
    <style>
        body {
            text-align: center;
            background-color: #ffe6e6;
            font-family: Arial, sans-serif;
            padding: 20px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }
        h1 {
            color: #ff4d4d;
            animation: fadeIn 2s ease-in-out;
        }
        p {
            font-size: 20px;
            color: #333;
            animation: fadeIn 3s ease-in-out;
        }
        .heart {
            font-size: 50px;
            animation: heartbeat 1s infinite;
        }
        .gif-container {
            margin-top: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .gif-container img {
            width: 200px;
            border-radius: 10px;
            animation: fadeIn 3s ease-in-out;
        }
        @keyframes heartbeat {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        /* Responsive Design für kleinere Bildschirme */
        @media screen and (max-width: 600px) {
            body {
                padding: 10px;
            }

            h1 {
                font-size: 24px;
            }

            p {
                font-size: 16px;
            }

            .gif-container img {
                width: 150px;
            }

            .heart {
                font-size: 40px;
            }
        }

        @media screen and (max-width: 1024px) {
            body {
                padding: 15px;
            }

            h1 {
                font-size: 28px;
            }

            p {
                font-size: 18px;
            }

            .gif-container img {
                width: 180px;
            }

            .heart {
                font-size: 45px;
            }
        }
    </style>
</head>
<body>
    <h1>To the girl with the cutest bun hair on earth!</h1>
    <p> The best people come unexpectedly..</p>
    <p> For me, you were like a shot of Espresso. 🌟</p>
    <p> I Wish you a wonderful Valentines Day, Melissa!</p> <p class="heart">💖</p>

    <div class="gif-container">
        <img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExaTViczVvdXdiZDZ4aWx4N3djbGk4MmkyazZ1amNzdGZkbG04MnJ1cCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/b4UHeUnzarvUnjl0fg/giphy.gif" alt="Cute Love Gif">
    </div>

    <audio controls autoplay loop>
        <source src="https://www.bensound.com/bensound-music/bensound-romantic.mp3" type="audio/mp3">
        Dein Browser unterstützt keine Audio-Wiedergabe.
    </audio>
</body>
</html>
