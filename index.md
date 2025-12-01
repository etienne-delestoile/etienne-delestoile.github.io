<style>
  /* COVER FULL-WIDTH, 2/3 OF SCREEN HEIGHT */
  .cover-photo {
    width: 100%;
    height: 66vh;                /* hauteur = 2/3 de la fenêtre */
    overflow: hidden;
    position: relative;
  }

  .cover-photo img {
    width: 100%;
    height: 100%;
    object-fit: cover;           /* on garde toute la largeur, léger zoom mais pas excessif */
    object-position: center;     /* centré */
    display: block;
  }

  /* PROFILE BLOCK (PHOTO + TEXTE) */
  .profile-section {
    max-width: 1100px;
    margin: -70px auto 2rem auto; /* fait remonter la photo sur la cover */
    padding: 0 1rem;
    display: flex;
    align-items: flex-start;
    gap: 2rem;
  }

  .profile-photo {
    flex: 0 0 auto;
  }

  .profile-photo img {
    width: 180px;
    height: 180px;
    object-fit: cover;
    border-radius: 6px;
    border: 4px solid white; 
    box-shadow: 0 2px 10px rgba(0,0,0,0.15);
  }

  .profile-text {
    flex: 1;
    padding-top: 1rem;
  }

  .profile-text .name {
    font-size: 1.6rem;
    font-weight: 600;
    margin-bottom: 0.3rem;
  }

  .profile-text p {
    margin: 0.2rem 0;
    line-height: 1.5;
  }
</style>

<!-- COVER -->
<div class="cover-photo">
  <img src="ciudad_garcia.jpg" alt="Cover image">
</div>

<!-- PROFILE SECTION -->
<div class="profile-section">

  <!-- PHOTO DE PROFIL -->
  <div class="profile-photo">
    <img src="photo_jeco.jpg" alt="Etienne de L'Estoile">
  </div>

  <!-- TEXTE À DROITE DE LA PHOTO -->
  <div class="profile-text">
    <div class="name">Etienne de L'Estoile</div>
    <p><strong>Climate & Macroeconomics Economist</strong></p>
    <p>Macroprudential Policy and Financial Stability Division, Banque de France</p>
    <p>PhD in Economics, Paris 1 Panthéon-Sorbonne</p>
  </div>

</div>

<nav class="site-nav">
  <a href="/">Home</a>
  <a href="/research">Research</a>
  <a href="/outreach">Outreach</a>
</nav>

<div class="content">

# About Me

I am an Economist in the Macroprudential Policy and Financial Stability Division at the Banque de France and hold a PhD in Economics from Paris 1 Panthéon-Sorbonne.  
My work focuses on the intersection of <strong>climate risks, macro-financial stability, and data-intensive modelling</strong>.

I develop empirical tools to quantify the exposure of firms, banks, and economic systems to environmental shocks, using high-resolution physical risk data, geospatial information, and granular balance-sheet microdata. My research is applied, policy-relevant, and aims to inform central banks, regulators, and institutions about emerging climate vulnerabilities.

---

## Research Interests

- Climate–macro linkages and environmental shocks  
- Natural disaster impacts & physical risk modelling  
- Macroprudential policy & financial stability  
- Commercial real estate & land-use economics  
- Spatial econometrics & geospatial modelling  

---

## Author Webpages

- <a href="https://www.banque-france.fr/fr/etienne-de-lestoile">Banque de France</a>  
- <a href="https://shs.cairn.info/publications-de-etienne-de-lestoile--699197?lang=fr">Cairn</a>

</div>
