<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Plan Technique - VAR Intelligent</title>
  <style>
    body { background: #0c0c0c; color: white; font-family: Arial; margin: 0; }
    header { background: #ffcc00; color: #111; padding: 15px; text-align: center; font-size: 26px; font-weight: bold; }
    main { padding: 20px; }
    h2 { color: #ffcc00; }
    .diagram { text-align: center; margin: 30px 0; }
    img { width: 90%; max-width: 600px; border-radius: 10px; border: 2px solid #ffcc00; }
    a.button { background: #ffcc00; color: #111; padding: 10px 20px; border-radius: 10px; text-decoration: none; font-weight: bold; }
  </style>
</head>
<body>
  <header>🧠 Plan Technique du Système VAR Intelligent</header>

  <main>
    <section>
      <h2>📡 Architecture Générale</h2>
      <p>Le système repose sur trois parties principales :</p>
      <ul>
        <li><strong>Caméras périphériques</strong> : enregistrent le match sous différents angles.</li>
        <li><strong>Serveur principal (IA + analyse vidéo)</strong> : traite les images, détecte les fautes et les hors-jeu.</li>
        <li><strong>Interface utilisateur</strong> : affiche le direct, le score, les alertes et les replays.</li>
      </ul>
    </section>

    <div class="diagram">
      <img src="https://i.ibb.co/fvZZtQM/var-diagram.png" alt="Schéma du système VAR scolaire">
    </div>

    <section>
      <h2>⚙️ Technologies utilisées</h2>
      <ul>
        <li>📷 WebRTC / OBS Studio pour la gestion multi-caméras</li>
        <li>🧠 Python + OpenCV + YOLOv8 pour la détection IA</li>
        <li>🌐 Node.js / React pour l’interface web</li>
        <li>🗄️ Base de données SQLite ou Firebase pour sauvegarder les replays</li>
        <li>🎙️ Reconnaissance vocale (SpeechRecognition API)</li>
      </ul>
    </section>

    <p style="text-align:center;">
      <a class="button" href="index.html">⬅️ Retour à l'accueil</a>
    </p>
  </main>
</body>
</html>
