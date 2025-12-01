<style>
  /* COVER : prendre plus de l'image (dézoom) mais plein écran */
  .cover-photo {
    width: 100%;
    height: 60vh;              /* hauteur = ~ 2/3 écran */
    overflow: hidden;
    position: relative;
    background: #000;
  }

  .cover-photo img {
    width: 100%;
    height: 100%;
    object-fit: cover;         /* style LinkedIn (mais zoom léger) */
    object-position: center;
    opacity: 0.95;             /* léger atténuation LinkedIn */
  }

  /* PROFILE PHOTO À GAUCHE, AU-DESSUS DE LA COVER */
  .profile-block {
    position: absolute;
    left: 40px;                /* marge gauche comme LinkedIn */
    bottom: -90px;             /* chevauchement vers le bas */
    display: flex;
    flex-direction: column;
    align-items: flex-start;   /* TOUT À GAUCHE */
    z-index: 10;
  }

  .profile-photo img {
    width: 170px;
    height: 170px;
    object-fit: cover;
    border-radius: 6px;        /* carré arrondi */
    border: 4px solid white;
    box-shadow: 0 4px 14px rgba(0,0,0,0.15);
  }

  .profile-name {
    margin-top: 10px;
    font-size: 1.7rem;
    font-weight: 700;
    color: #111;
  }

  /* DESCRIPTION : SOUS LA COVER, ALIGNÉE SUR LA COLONNE DE GAUCHE */
  .profile-description {
    max-width: 900px;
    margin: 120px 0 2rem 40px; /* aligné à 40px comme la photo */
    font-size: 1.05rem;
    line-height: 1.5;
  }
</style>

<!-- COVER -->
<div class="cover-photo">
  <img src="ciudad_garcia.jpg" alt="Cover image">
</div>

<!-- PROFILE BLOCK (PHOTO + NOM) -->
<div class="profile-block">
  <div class="profile-photo">
    <img src="photo_jeco.jpg" alt="Etienne de L'Estoile">
  </div>
  <div class="profile-name">Etienne de L'Estoile</div>
</div>

<!-- DESCRIPTION (sous la cover) -->
<div class="profile-description">
  <p><strong>Climate & Macroeconomics Economist</strong><br>
     Macroprudential Policy and Financial Stability Division, Banque de France<br>
     PhD in Economics, Paris 1 Panthéon-Sorbonne
  </p>
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
