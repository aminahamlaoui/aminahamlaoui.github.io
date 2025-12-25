# aminahamlaoui.github.io
Site de présentation et de ressources en ligne, créé avec GitHub Pages
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Teranza – Présentation</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: Arial, Helvetica, sans-serif;
      line-height: 1.6;
      background: #f5f6f8;
      color: #222;
    }
    header {
      padding: 60px 20px;
      background: #ffffff;
      border-bottom: 1px solid #e0e0e0;
    }
    .container {
      max-width: 1100px;
      margin: auto;
      padding: 0 20px;
    }
    h1 { font-size: 2.2rem; margin-bottom: 15px; }
    h2 { font-size: 1.6rem; margin-bottom: 10px; }
    p { margin-bottom: 15px; color: #555; }
    section {
      padding: 50px 0;
      background: #ffffff;
      margin-bottom: 20px;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: #fafafa;
      padding: 25px;
      border-radius: 8px;
      border: 1px solid #e5e5e5;
    }
    .hero {
      display: grid;
      grid-template-columns: 1.2fr 0.8fr;
      gap: 30px;
      align-items: center;
    }
    .hero-box {
      background: #fafafa;
      padding: 30px;
      border-radius: 10px;
      border: 1px solid #e5e5e5;
    }
    .contact {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 30px;
    }
    form input, form textarea {
      width: 100%;
      padding: 12px;
      margin-bottom: 12px;
      border-radius: 6px;
      border: 1px solid #ccc;
      font-size: 0.95rem;
    }
    form button {
      padding: 12px;
      width: 100%;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-size: 1rem;
    }
    footer {
      text-align: center;
      padding: 25px 15px;
      font-size: 0.9rem;
      color: #777;
    }
    @media (max-width: 768px) {
      .hero, .contact { grid-template-columns: 1fr; }
    }
  </style>
</head>
<body>

  <header>
    <div class="container hero">
      <div>
        <h1>Teranza – Accompagnement éducatif et soutien scolaire</h1>
        <p>
          Teranza est une micro-entreprise multifonctionnelle spécialisée dans
          l'accompagnement pédagogique et le soutien scolaire.
        </p>
        <p>
          Nous proposons des solutions adaptées aux besoins des élèves, en
          présentiel à domicile ou en ligne via la plateforme Google Meet.
        </p>
      </div>
      <div class="hero-box">
        <h2>Notre mission</h2>
        <p>• Favoriser la réussite scolaire à tous les niveaux</p>
        <p>• Offrir un encadrement sérieux et personnalisé</p>
        <p>• S'adapter au rythme et aux objectifs de chaque élève</p>
      </div>
    </div>
  </header>

  <section>
    <div class="container">
      <h2>À propos de Teranza</h2>
      <p>
        Teranza accompagne les élèves de tous niveaux à travers des cours
        particuliers et des classes spécialisées, avec une approche pédagogique
        claire, structurée et efficace.
      </p>
    </div>
  </section>

  <section>
    <div class="container">
      <h2>Nos services</h2>
      <div class="grid">
        <div class="card">
          <h3>Cours particuliers</h3>
          <p>
            Cours de mathématiques, aide aux devoirs et langue arabe, dispensés à
            domicile ou en ligne.
          </p>
        </div>
        <div class="card">
          <h3>Enseignement en ligne</h3>
          <p>
            Cours à distance via Google Meet, accessibles partout et adaptés à
            tous les niveaux scolaires.
          </p>
        </div>
        <div class="card">
          <h3>Classes de préparation</h3>
          <p>
            Préparation encadrée pour les examens du Brevet et du Baccalauréat.
          </p>
        </div>
      </div>
    </div>
  </section>

  <section>
    <div class="container">
      <h2>Tarification</h2>
      <p>
        Les tarifs commencent à partir de <strong>15 € par heure</strong> et
        varient en fonction du niveau et du type d'accompagnement choisi.
      </p>
    </div>
  </section>

  <section>
    <div class="container">
      <h2>Contact</h2>
      <div class="contact">
        <div class="card">
          <h3>Coordonnées</h3>
          <p>Email : contact@teranza.com</p>
          <p>Téléphone : À renseigner</p>
          <p>Mode : Présentiel & En ligne</p>
        </div>
        <div class="card">
          <h3>Formulaire de contact</h3>
          <form>
            <input type="text" placeholder="Nom et prénom" required />
            <input type="email" placeholder="Adresse e-mail" required />
            <textarea rows="4" placeholder="Votre message"></textarea>
            <button type="submit">Envoyer</button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <footer>
    © 2025 – Teranza | Tous droits réservés
  </footer>

</body>
</html>






