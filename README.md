<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>APP</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
</head>
<body>
    <nav>
        <ul>
            <li><a href="#"><span class="material-icons">home</span> Accueil</a></li>
            <li><a href="asitepresentation.html"><span class="material-icons">school</span> Exercice</a></li>
        </ul>
    </nav>
    
    <h1> <u>Les App</u></h1>

    <div class="container">
        <div class="game" onclick="window.location.href = 'trouvelenumber.html';">
            <span class="material-icons">filter_1</span>
            <h2>Trouve le Numéro</h2>
        </div>

        <div class="game" onclick="window.location.href = 'promotion.html';">
            <span class="material-icons">local_offer</span>
            <h2>Réduction %</h2>
        </div>
  
        <div class="game" onclick="window.location.href = 'aleatoire.html';">
            <span class="material-icons">shuffle</span>
            <h2>Aléatoire</h2>
        </div>

        <div class="game" onclick="window.location.href = 'shifoumie.html';">
            <span class="material-icons">gesture</span>
            <h2>Chifoumi</h2>
        </div>

        <div class="game" onclick="window.location.href = 'nombrepremier.html';">
            <span class="material-icons">filter_none</span>
            <h2>Nombre Premier</h2>
        </div>

        <div class="game" onclick="window.location.href = 'loto.html';">
            <span class="material-icons">casino</span>
            <h2>Loto</h2>
        </div>

        <div class="game" onclick="window.location.href = 'dessin.html';">
            <span class="material-icons">brush</span>
            <h2>Dessin</h2>
        </div>
    </div>
    
</body>
</html>

        <style>
         body {
            font-family: 'Roboto', sans-serif;
            background-color: #292f3f;
            color: #fff;
            margin: 0;
            padding: 0;
        }

        nav {
            background: linear-gradient(to right, #292f3f, #007bff);
            padding: 20px 0;
            position: sticky;
            top: 0;
            z-index: 10;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: space-around;
            max-width: 960px;
            margin: 0 auto;
        }

        nav li a {
            color: #fff;
            text-decoration: none;
            font-size: 18px;
            transition: color 0.3s ease;
        }

        nav li a:hover {
            color: #292f3f;
        }

        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            align-items: center;
            max-width: 960px;
            margin: 50px auto;
            padding: 0 20px;
        }

        h1 {
            text-align: center;
            font-size: 36px;
            margin-top: 40px;
        }

        .game {
            flex-basis: calc(33.33% - 40px);
            background-color: #007bff;
            border-radius: 10px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 200px;
            margin-bottom: 30px;
            transition: background-color 0.3s ease, transform 0.3s ease;
            cursor: pointer;
            box-shadow: 0px 5px 15px rgba(0,0,0,0.1);
        }

        .game:hover {
            background-color: #0056b3;
            transform: translateY(-10px);
        }

        h2 {
            font-size: 24px;
            text-align: center;
        }

        @media (max-width: 768px) {
            .game {
                flex-basis: 100%;
                margin-bottom: 20px;
            }
        }

        .material-icons {
            font-size: 48px;
            margin-bottom: 10px;
        }
    </style>
