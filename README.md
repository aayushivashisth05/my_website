<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>I'm Sorry</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
        }
        .card {
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
            max-width: 400px;
        }
        h1 {
            color: #e63946;
            font-size: 2em;
        }
        p {
            font-size: 1.2em;
            color: #555;
        }
        .heart {
            color: red;
            font-size: 2em;
            animation: heartbeat 1.5s infinite;
        }
        @keyframes heartbeat {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }
        .button {
            background: #ff6b6b;
            color: white;
            padding: 10px 20px;
            border-radius: 8px;
            text-decoration: none;
            font-weight: bold;
            display: inline-block;
            margin-top: 10px;
        }
        .button:hover {
            background: #e63946;
        }
    </style>
</head>
<body>
    <div class="card">
        <h1>I'm Sorry 💔</h1>
        <p>I know I made a mistake, and it hurts me to know that I hurt you.</p>
        <p>Will you forgive me? <span class="heart">❤️</span></p>
        <a href="https://yourdomain.com" class="button">Let's Make It Right</a>
    </div>
</body>
</html>
