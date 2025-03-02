<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Воспроизведение звука</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
        }
        button {
            padding: 20px 40px;
            font-size: 24px;
            cursor: pointer;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

<button onclick="playSound()">Нажми меня!</button>

<audio id="audio" src="kaef.mp3"></audio>

<script>
    function playSound() {
        var audio = document.getElementById("audio");
        audio.play();
    }
</script>

</body>
</html>
