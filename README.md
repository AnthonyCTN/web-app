<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Application</title>
</head>
<body>
    <nav>
        <ul>
            <li><a href="#">Accueil</a></li>
            <li><a href="asitepresentation.html">Exercice</a></li>
        </ul>
    </nav>
    
  <h1>Mes Jeux</h1>

  <div class="container">
  
  <div class="game" onclick="window.location.href = 'trouvelenumber.html';">
    <h2>Trouve le Numéro</h2>
  </div>

  <div class="game" onclick="window.location.href = 'promotion.html';">
    <h2>Calcul %</h2>
  </div>
  
  <div class="game" onclick="window.location.href = 'shifoumie.html';">
    <h2>Chifoumi</h2>
  </div>
  
  <div class="game" onclick="window.location.href = 'nombrepremier.html';">
    <h2>Nombre Premier</h2>
  </div>

  <div class="game" onclick="window.location.href = 'loto.html';">
    <h2>Loto</h2>
  </div>

  <div class="game" onclick="window.location.href = 'dessin.html';">
    <h2>Dessin</h2>
  </div>

 </div>



</body>
</html>




  <style>
    body {
        font-family: Arial, sans-serif;
        background-color: #292f3f;
    }
    
    .container {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        max-width: 960px;
        margin: 0 auto;
        padding: 20px;
    }
    
    h1 {
      color: #fff;
      font-size: 36px;
      margin-bottom: 40px;
      text-align: center;
     
    }
    
    .game {
      width: 200px;
      height: 200px;
      background-color: #007bff;
      border-radius: 10px;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      margin: 20px;
      transition: background-color 0.3s ease;
    }
    
    .game:hover {
      background-color: #0056b3;
    }
    
    h2 {
      color: #fff;
      font-size: 24px;
      text-align: center;
    }

    nav {
            background-color: #292f3f;
            padding: 10px;
           
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }

        nav li {
            margin: 0 10px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            font-size: 18px;
        }

        nav a:hover {
            color: #007bff;
        }
   
  </style>


