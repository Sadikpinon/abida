<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For My Love, Faozia</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to right, #ff758c, #ff7eb3);
            color: white;
            text-align: center;
        }
        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            padding: 20px;
        }
        .name-container {
            perspective: 1000px;
            width: 400px;
            height: 100px;
            margin-bottom: 20px;
        }
        .name-card {
            width: 100%;
            height: 100%;
            position: relative;
            transform-style: preserve-3d;
            transition: transform 0.8s;
        }
        .name-card:hover {
            transform: rotateY(180deg);
        }
        .name-front, .name-back {
            position: absolute;
            width: 100%;
            height: 100%;
            backface-visibility: hidden;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2em;
            font-weight: bold;
            border-radius: 10px;
            box-shadow: 2px 2px 15px rgba(255, 255, 255, 0.3);
        }
        .name-front {
            background: rgba(255, 255, 255, 0.2);
        }
        .name-back {
            background: #fff;
            color: #ff758c;
            transform: rotateY(180deg);
        }
        .card-container {
            perspective: 1000px;
            margin: 20px;
        }
        .card {
            width: 300px;
            height: 300px;
            position: relative;
            transform-style: preserve-3d;
            transition: transform 0.8s;
        }
        .card:hover {
            transform: rotateY(180deg);
        }
        .card-front, .card-back {
            position: absolute;
            width: 100%;
            height: 100%;
            backface-visibility: hidden;
            display: flex;
            align-items: center;
            justify-content: center;
            border-radius: 10px;
            box-shadow: 2px 2px 15px rgba(255, 255, 255, 0.3);
        }
        .card-front {
            background: rgba(255, 255, 255, 0.2);
            padding: 15px;
        }
        .card-back {
            background: #fff;
            transform: rotateY(180deg);
        }
        .card-back img {
            width: 100%;
            height: 100%;
            border-radius: 10px;
        }
        .footer {
            margin-top: 30px;
            font-size: 1.2em;
            font-style: italic;
            opacity: 0.8;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="name-container">
            <div class="name-card">
                <div class="name-front">Faozia Abida Shoptorshi</div>
                <div class="name-back">I Love You, Sexxa ❤️</div>
            </div>
        </div>
        <div class="heart">❤️</div>
        <div class="card-container">
            <div class="card">
                <div class="card-front">
                    <p>You are the light of my life, the reason my heart beats faster, and the one who makes my world beautiful. 
                    Your kindness, intelligence, and beauty amaze me every day, and I am endlessly grateful to have you in my life. 
                    You are my love, my happiness, and my forever.</p>
                </div>
                <div class="card-back">
                    <img src="abida.jpeg" alt="Beautiful Memory">
                </div>
            </div>
        </div>
        <div class="card-container">
            <div class="card">
                <div class="card-front">
                    <p>Sexxa, you came back into my life after two years, and I can't express how grateful I am. Thank you for returning and making me the happiest person alive. 
                    You mean everything to me, and I never want you to leave me again. You are my heart, my soul, and my forever love.</p>
                </div>
                <div class="card-back">
                    <img src="abida2.jpeg" alt="Special Moment">
                </div>
            </div>
        </div>
        <div class="footer">Forever yours, with all my love.</div>
    </div>
</body>
</html>
