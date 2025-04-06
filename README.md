# RRJKsboutique


<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>RRJKS - Boutique de Logos</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      background-color: #0e0e0e;
      color: white;
    }
    header {
      background: #1f1f1f;
      padding: 20px;
      text-align: center;
      font-size: 2rem;
      color: #f44336;
    }
    .container {
      padding: 20px;
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 20px;
      max-width: 1200px;
      margin: auto;
    }
    .card {
      background: #1a1a1a;
      border-radius: 16px;
      padding: 16px;
      box-shadow: 0 0 10px #f44336;
    }
    .card img {
      width: 100%;
      border-radius: 12px;
    }
    .card h2 {
      margin-top: 10px;
      font-size: 1.5rem;
    }
    .card p {
      margin: 10px 0;
    }
    .card a {
      display: inline-block;
      margin-top: 10px;
      background: #f44336;
      color: white;
      padding: 10px 20px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #111;
      color: #666;
    }
  </style>
</head>
<body>
  <header>
    🛍️ RRJKS - Boutique de Logos Personnalisés
  </header>

  <div class="container">
    <div class="card">
      <img src="logo-gaming.jpg" alt="Logo Gaming Twitch RRJKS">
      <h2>Logo Gaming Twitch</h2>
      <p>💰 9,99 €<br>🎨 Personnalisé à la demande (pseudo, couleurs, style...)</p>
      <a href="https://www.paypal.com/paypalme/tonlienpaypal">Acheter maintenant</a>
    </div>

    <div class="card">
      <img src="logo-youtube.jpg" alt="Logo YouTube RRJKS">
      <h2>Logo YouTube</h2>
      <p>💰 9,99 €<br>🎨 Créé selon ton univers (chaîne, ambiance, etc.)</p>
      <a href="https://www.paypal.com/paypalme/tonlienpaypal">Acheter maintenant</a>
    </div>
  </div>

  <footer>
    Après paiement, vous recevrez un lien pour remplir votre demande de personnalisation ✏️
  </footer>
</body>
</html>
