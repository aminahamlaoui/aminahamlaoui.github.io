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
      background: #d4f7d4; /* vert clair */
      color: #000; /* paragraphe en noir */
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
    h1 { 
      font-size: 2.2rem; 
      margin-bottom: 15px; 
      color: #556B2F; /* vert militaire foncé */
    }
    h2 { 
      font-size: 1.6rem; 
      margin-bottom: 10px; 
      color: #556B2F; /* vert militaire foncé */
    }
    h3, h4 {
      color: #000; /* sous-titres en noir */
    }
    p { 
      margin-bottom: 15px; 
      color: #000; /* paragraphe en noir */
    }
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
    .card, .hero-box {
      background: #f5e0a1; /* jaune sable */
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
      background-color: #d4f7d4; /* vert clair même que le fond */
      color: #000;
    }
    form button:hover {
      background-color: #b7e6b7; /* légèrement plus foncé au hover */
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
    /* Style bouton lien vers contact */
    .btn-contact {
      display:block;
      margin-top:20px;
      padding:14px;
      width:100%;
      border:none;
      border-radius:8px;
      font-size:1rem;
      cursor:pointer;
      text-align:center;
      background-color:#d4f7d4; /* vert clair */
      color:#000;
      text-decoration:none;
    }
    .btn-contact:hover {
      background-color: #b7e6b7; /* légèrement plus foncé au hover */
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
      <h2>Tarification</h2>
      <div style="display:grid; grid-template-columns: 1.2fr 0.8fr; gap:30px; align-items:stretch;">
        
        <!-- Bloc texte -->
        <div class="card">
          <h3 style="font-size:1.4rem; margin-bottom:10px;">Tarifs des cours particuliers</h3>
          <p style="font-size:1.1rem;">
            Les cours Teranza sont proposés à partir de
            <strong style="font-size:1.3rem;">15 € / heure</strong>.
          </p>
          <p>
            Nous trouvons une solution adaptée à chaque élève, quels que soient
            son niveau, ses objectifs et le mode d’enseignement choisi
            (à domicile ou en ligne).
          </p>

          <div style="margin-top:20px;">
            <h4>Flexibilité totale</h4>
            <p>
              Commencez par une première séance et poursuivez uniquement si vous
              êtes satisfait(e). La fréquence et la durée des cours sont
              entièrement personnalisables.
            </p>
          </div>
        </div>

        <!-- Carte tarif -->
        <div class="card">
          <h3 style="font-size:1.6rem; margin-bottom:15px;">
            À partir de <span style="font-size:2rem;">15 € / h</span>
          </h3>

          <p><strong>Inclus :</strong></p>
          <ul style="list-style:none; padding-left:0; line-height:1.8;">
            <li>✔ Cours particuliers tous niveaux</li>
            <li>✔ Mathématiques, aide aux devoirs et langue arabe</li>
            <li>✔ À domicile ou en ligne (Google Meet)</li>
            <li>✔ Préparation Brevet et Baccalauréat</li>
            <li>✔ Suivi personnalisé de l’élève</li>
            <li>✔ Classes individuelles ou en petit groupe</li>
          </ul>

          <!-- Bouton lien vers formulaire contact -->
          <a href="#contact" class="btn-contact">
            Contacter pour plus d’informations
          </a>
        </div>
      </div>
    </div>
  </section>

  <section id="contact">
    <div class="container">
      <h2>Contact</h2>
      <div class="contact">
        <div class="card">
          <h3>Coordonnées</h3>
          <p>Email : contact@teranza.com</p>
          <p>Téléphone : 07 66 80 51 23</p>
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

  
  
   

     
   

       

       
        
 

  






