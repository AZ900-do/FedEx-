# FedEx-
Participants gagnant un jeu de rou 
<!DOCTYPE html><html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Jeu de la Roue</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background: #f3f3f3;
      padding: 20px;
    }
    h1 {
      color: #333;
    }
    #wheel {
      width: 300px;
      height: 300px;
      margin: 20px auto;
      border-radius: 50%;
      border: 10px solid #555;
      position: relative;
      overflow: hidden;
      transform: rotate(0deg);
      transition: transform 5s cubic-bezier(0.33, 1, 0.68, 1);
    }
    .slice {
      position: absolute;
      width: 50%;
      height: 50%;
      transform-origin: 100% 100%;
      background: #ddd;
      color: #000;
      text-align: right;
      padding: 10px;
      box-sizing: border-box;
    }
    #spinBtn {
      padding: 10px 20px;
      font-size: 18px;
      background-color: #28a745;
      color: white;
      border: none;
      cursor: pointer;
      margin: 20px;
    }
    #result, #formulaire {
      display: none;
    }
    #formulaire input {
      padding: 10px;
      margin: 5px;
      width: 80%;
    }
    #formulaire button {
      padding: 10px 20px;
      background-color: #007bff;
      color: white;
      border: none;
    }
  </style>
</head>
<body>
  <h1>Tourne la Roue et Gagne un Cadeau !</h1>  <div id="wheel">
    <div class="slice" style="background:#FFD700; transform: rotate(0deg);">Ordinateur</div>
    <div class="slice" style="background:#DC143C; transform: rotate(90deg);">60.000€</div>
    <div class="slice" style="background:#20B2AA; transform: rotate(180deg);">Voiture</div>
    <div class="slice" style="background:#9370DB; transform: rotate(270deg);">Surprise</div>
  </div><button id="spinBtn">Tourner la Roue</button>

  <div id="result"></div>  <div id="form
