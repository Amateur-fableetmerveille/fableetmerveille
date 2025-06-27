<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fable et Merveille - Accueil</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to bottom, #fdf6f0, #ffe8cc);
      color: #333;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #ffa94d;
      color: white;
      text-align: center;
      padding: 2rem 1rem;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    nav {
      display: flex;
      justify-content: center;
      background: #ffd8a8;
      padding: 1rem;
      gap: 2rem;
    }
    nav a {
      text-decoration: none;
      color: #5c3d00;
      font-weight: bold;
    }
    main {
      padding: 2rem;
      text-align: center;
    }
    .btn {
      padding: 1rem 2rem;
      background-color: #ffa94d;
      color: white;
      border: none;
      border-radius: 10px;
      font-size: 1rem;
      cursor: pointer;
      transition: background-color 0.3s;
    }
    .btn:hover {
      background-color: #ff922b;
    }
    footer {
      background-color: #ffa94d;
      color: white;
      text-align: center;
      padding: 1rem;
      position: fixed;
      width: 100%;
      bottom: 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>Bienvenue sur Fable et Merveille</h1>
    <p>Des histoires magiques pour petits et grands</p>
  </header>

  <nav>
    <a href="#histoires">Histoires</a>
    <a href="#videos">Vidéos</a>
    <a href="#contact">Contact</a>
  </nav>

  <main>
    <h2>Explorez un monde enchanté</h2>
    <p>Découvrez nos contes, fables et merveilles pleins de magie et d'aventures.</p>
    <button class="btn" onclick="afficherMessage()">Clique ici pour une surprise !</button>
    <div id="message" style="margin-top: 2rem; font-size: 1.2rem;"></div>
  </main>

  <footer>
    &copy; 2025 Fable et Merveille. Tous droits réservés.
  </footer>

  <script>
    function afficherMessage() {
      const messageDiv = document.getElementById('message');
      messageDiv.textContent = "✨ Merci d'être ici ! Que la magie t'accompagne ✨";
    }
  </script>
</body>
</html>
