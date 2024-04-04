<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Признание в Любви</title>
<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f3f3f3;
    }
    .container {
        text-align: center;
        margin-top: 100px;
    }
    h1 {
        color: #333;
        font-size: 3em;
        margin-bottom: 20px;
    }
    #heart {
        font-size: 100px;
        color: red;
        animation: heartbeat 1s infinite alternate;
    }
    @keyframes heartbeat {
        from {
            transform: scale(1);
        }
        to {
            transform: scale(1.2);
        }
    }
    button {
        padding: 10px 20px;
        background-color: #4CAF50;
        color: white;
        border: none;
        cursor: pointer;
        font-size: 1.2em;
        border-radius: 5px;
    }
    button:hover {
        background-color: #45a049;
    }
</style>
</head>
<body>

<div class="container">
    <h1>Дорогая Лейла, няша моя,</h1>
    <div id="heart">❤️</div>
    <p>Я хочу признаться тебе в своих чувствах. Ты для меня означаешь всё, и я не могу представить свою жизнь без тебя.</p>
    <p>Ты самое прекрасное, что мне когда-либо встречалось, и я люблю тебя.</p>
    <button onclick="showMessage()">Хочу тебе что-то сказать</button>
    <p id="secret-message" style="display:none; margin-top: 20px;">Ты уникальная, и я надеюсь, что ты разделаешь мои чувства.</p>
</div>

<script>
    function showMessage() {
        document.getElementById("secret-message").style.display = "block";
    }
</script>

</body>
</html>
