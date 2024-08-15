<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Te Amo ❤️🤟</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
            font-family: 'Arial', sans-serif;
        }
        .heart-container {
            text-align: center;
            animation: fadeIn 2s ease-in-out;
        }
        .heart {
            font-size: 100px;
            color: red;
            animation: pulse 1.5s infinite;
        }
        .message {
            font-size: 24px;
            margin-top: 20px;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
</head>
<body>
    <div class="heart-container">
        <div class="heart">❤️</div>
        <div class="message">Te amo ❤️🤟</div>
    </div>
</body>
</html>
