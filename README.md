# Birthday-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday Hansika!</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(120deg, #ff9a9e, #fad0c4);
            color: #333;
            text-align: center;
            padding: 50px;
            overflow: hidden;
        }
        .container {
            margin: auto;
            padding: 20px;
            max-width: 600px;
            background: rgba(255, 255, 255, 0.8);
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            animation: fadeIn 2s ease-in-out;
        }
        h1 {
            font-size: 3em;
            color: #ff6f61;
        }
        p {
            font-size: 1.2em;
            margin-top: 20px;
        }
        .balloons img {
            width: 100px;
            margin: 10px;
            animation: float 3s ease-in-out infinite;
        }
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: scale(0.8);
            }
            to {
                opacity: 1;
                transform: scale(1);
            }
        }
        @keyframes float {
            0% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-20px);
            }
            100% {
                transform: translateY(0);
            }
        }
        .music {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Happy Birthday, Hansika! 🎉</h1>
        <p>Wishing you a day filled with love, laughter, and all your favorite things. You deserve the best! 💖</p>
        <div class="balloons">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3b/Red_balloon.svg/1200px-Red_balloon.svg.png" alt="Red Balloon">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7f/Yellow_balloon.svg/1200px-Yellow_balloon.svg.png" alt="Yellow Balloon">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/db/Blue_balloon.svg/1200px-Blue_balloon.svg.png" alt="Blue Balloon">
        </div>
        <div class="music">
            <audio controls autoplay loop>
                <source src="https://www.bensound.com/bensound-music/bensound-happy.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
        </div>
    </div>
</body>
</html>
