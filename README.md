<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Saadoukou Ouedraogo | Développeur Fullstack</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      background: linear-gradient(135deg, #0f172a, #111827, #1e293b);
      color: #f8fafc;
      line-height: 1.6;
      padding: 30px 15px;
    }

    .container {
      max-width: 1100px;
      margin: 0 auto;
    }

    .card {
      background: rgba(255, 255, 255, 0.06);
      border: 1px solid rgba(255, 255, 255, 0.08);
      backdrop-filter: blur(10px);
      border-radius: 20px;
      padding: 30px;
      margin-bottom: 25px;
      box-shadow: 0 10px 35px rgba(0, 0, 0, 0.25);
    }

    .hero {
      text-align: center;
      padding: 60px 30px;
    }

    .hero h1 {
      font-size: 2.8rem;
      font-weight: 800;
      margin-bottom: 10px;
      color: #ffffff;
    }

    .hero h2 {
      font-size: 1.2rem;
      font-weight: 500;
      color: #38bdf8;
      margin-bottom: 20px;
    }

    .hero p {
      max-width: 750px;
      margin: 0 auto;
      color: #cbd5e1;
      font-size: 1.05rem;
    }

    .section-title {
      font-size: 1.5rem;
      margin-bottom: 20px;
      color: #ffffff;
      position: relative;
      padding-left: 18px;
    }

    .section-title::before {
      content: "";
      position: absolute;
      left: 0;
      top: 5px;
      width: 6px;
      height: 28px;
      border-radius: 10px;
      background: linear-gradient(180deg, #38bdf8, #0ea5e9);
    }

    .about p,
    .vision p {
      color: #dbeafe;
      font-size: 1rem;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 20px;
    }

    .skill-box,
    .project-box {
      background: rgba(255, 255, 255, 0.05);
      border-radius: 16px;
      padding: 20px;
      border: 1px solid rgba(255, 255, 255, 0.06);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .skill-box:hover,
    .project-box:hover {
      transform: translateY(-6px);
      box-shadow: 0 12px 25px rgba(14, 165, 233, 0.15);
    }

    .skill-box h3,
    .project-box h3 {
      color: #38bdf8;
      margin-bottom: 10px;
      font-size: 1.1rem;
    }

    .skill-box p,
    .project-box p {
      color: #cbd5e1;
      font-size: 0.95rem;
    }

    .contact-links {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      justify-content: center;
      margin-top: 20px;
    }

    .contact-links a {
      text-decoration: none;
      color: #fff;
      background: linear-gradient(135deg, #0ea5e9, #2563eb);
      padding: 12px 20px;
      border-radius: 12px;
      font-weight: 600;
      transition: all 0.3s ease;
      display: inline-block;
    }

    .contact-links a:hover {
      transform: translateY(-3px);
      opacity: 0.92;
    }

    .stats {
      text-align: center;
    }

    .stats img {
      max-width: 100%;
      border-radius: 14px;
      margin: 10px;
    }

    .footer {
      text-align: center;
      color: #94a3b8;
      padding: 20px 10px;
      font-size: 0.95rem;
    }

    .badge {
      display: inline-block;
      margin-top: 18px;
      padding: 8px 16px;
      border-radius: 999px;
      background: rgba(56, 189, 248, 0.12);
      color: #7dd3fc;
      font-size: 0.9rem;
      font-weight: 600;
      border: 1px solid rgba(56, 189, 248, 0.2);
    }

    @media (max-width: 768px) {
      .hero h1 {
        font-size: 2.1rem;
      }

      .hero h2 {
        font-size: 1rem;
      }

      .card {
        padding: 22px;
      }
    }
  </style>
</head>
<body>
  <div class="container">

    <section class="card hero">
      <h1>Salut, je suis Saadoukou Ouedraogo</h1>
      <h2>Développeur Fullstack • Créateur de solutions SaaS • Entrepreneur Tech</h2>
      <p>
        Je conçois et développe des applications web, mobiles et desktop modernes,
        robustes et orientées métier. Mon objectif n’est pas juste de coder, mais de
        créer des solutions utiles, scalables et capables de générer de la vraie valeur.
      </p>
      <span class="badge">Django • Angular • Flutter • PostgreSQL</span>
    </section>

    <section class="card about">
      <h2 class="section-title">À propos</h2>
      <p>
        Développeur passionné par la création de produits digitaux efficaces, je travaille
        principalement sur des solutions de gestion, des plateformes SaaS, des outils métiers
        et des applications à fort potentiel business.
        J’aime transformer une idée en un produit concret, professionnel et exploitable.
      </p>
    </section>

    <section class="card">
      <h2 class="section-title">Expertise</h2>
      <div class="grid">
        <div class="skill-box">
          <h3>Backend</h3>
          <p>Django, Django REST Framework, architecture métier, API REST, sécurité, logique applicative.</p>
        </div>
        <div class="skill-box">
          <h3>Frontend</h3>
          <p>Angular, interfaces modernes, dashboards, expérience utilisateur claire et professionnelle.</p>
        </div>
        <div class="skill-box">
          <h3>Mobile & Desktop</h3>
          <p>Flutter pour créer des applications mobiles et desktop fluides, propres et évolutives.</p>
        </div>
        <div class="skill-box">
          <h3>Base de données</h3>
          <p>PostgreSQL, SQLite, modélisation de données, performance, structuration et fiabilité.</p>
        </div>
      </div>
    </section>

    <section class="card">
      <h2 class="section-title">Projets & Vision</h2>
      <div class="grid">
        <div class="project-box">
          <h3>GeniTeams</h3>
          <p>Plateforme SaaS de gestion d’équipes, pointage, fiches journalières et collaboration d’entreprise.</p>
        </div>
        <div class="project-box">
          <h3>GestioStock</h3>
          <p>Solution de gestion commerciale et de stock pensée pour les réalités terrain et les PME africaines.</p>
        </div>
        <div class="project-box">
          <h3>GestioCompta</h3>
          <p>Outil de comptabilité et de gestion financière simple, rapide et exploitable au quotidien.</p>
        </div>
        <div class="project-box">
          <h3>eFerme</h3>
          <p>Plateforme intelligente dédiée à la gestion agricole, au suivi des ressources et à la performance terrain.</p>
        </div>
      </div>
    </section>

    <section class="card vision">
      <h2 class="section-title">Ma vision</h2>
      <p>
        Je veux construire des solutions technologiques sérieuses, adaptées à nos réalités,
        et capables d’aider les entreprises, structures et entrepreneurs à mieux travailler,
        mieux suivre leurs activités et mieux grandir.
      </p>
    </section>

    <section class="card">
      <h2 class="section-title">Liens utiles</h2>
      <div class="contact-links">
        <a href="mailto:osaadoukou@gmail.com">Email</a>
        <a href="tel:+22675364491">Téléphone</a>
        <a href="https://github.com/sidiki-codeur" target="_blank">GitHub</a>
        <a href="https://github.com/sidiki-codeur/ressources-utiles" target="_blank">Ressources utiles</a>
      </div>
    </section>

    <section class="card stats">
      <h2 class="section-title">Statistiques GitHub</h2>
      <img src="https://github-readme-stats.vercel.app/api?username=sidiki-codeur&show_icons=true&theme=tokyonight" alt="GitHub Stats">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=sidiki-codeur&theme=tokyonight" alt="GitHub Streak">
    </section>

    <footer class="footer">
      Merci de visiter mon profil. Les projets sérieux, les collaborations utiles et les idées ambitieuses sont les bienvenus.
    </footer>

  </div>
</body>
</html>
