# pramodtripasa.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>I’m Sorry ❤️</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', sans-serif;
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .card {
            background: white;
            padding: 40px;
            max-width: 400px;
            text-align: center;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }

        h1 {
            color: #e63946;
            font-size: 32px;
        }

        p {
            color: #444;
            font-size: 18px;
            line-height: 1.6;
        }

        .heart {
            font-size: 50px;
            animation: beat 1s infinite;
        }

        @keyframes beat {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.2); }
        }

        button {
            margin-top: 20px;
            padding: 12px 25px;
            font-size: 16px;
            border: none;
            border-radius: 25px;
            background: #e63946;
            color: white;
            cursor: pointer;
        }

        button:hover {
            background: #d62828;
        }
    </style>
</head>
<body>

    <div class="card">
        <div class="heart">❤️</div>
        <h1>I’m Sorry</h1>
        <p>
            I know I hurt you, and I truly regret it.<br>
            Please believe me when I say you mean the world to me.<br>
            I promise to do better.
        </p>
        <button onclick="alert('Thank you for giving me another chance ❤️')">
            Forgive Me?
        </button>
    </div>

</body>
</html>
