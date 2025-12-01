<style>
  /* COVER = pleine largeur, 2/3 de la hauteur de l’écran */
  .cover-photo {
    width: 100%;
    height: 66vh;
    overflow: hidden;
  }

  .cover-photo img {
  width: 100%;
  height: 100%;
  object-fit: contain;  
  object-position: center;
  background: #000; /* fond noir derrière si bords */
  display: block;
}


  /* PROFILE CENTRÉ + AU-DESSUS DE LA COVER */
  .profile-wrapper {
    width: 100%;
    display: flex;
    justify-content: center;
    margin-top: -90px; /* remonte la photo pour la faire chevaucher */
    pointer-events: none; /* empêche bugs hover */
  }

  .profile-photo {
    text-align: center;
  }

  .profile-photo img {
    width: 180px;
    height: 180px;
    border-radius: 6px; /* carré arrondi */
    object-fit: cover;
    border: 4px solid white;
    box-shadow: 0 3px 12px rgba(0,0,0,0.15);
    background: white;
    pointer-events: auto;
  }

  .profile-name {
    font-size: 1.6rem;
    font-weight: 600;
    margin-top: 0.5rem;
    text-align: center;
  }

  /* DESCRIPTION SOUS LA COVER */
  .profile-description {
    max-width: 900px;
    margin: 1.5rem auto 2rem auto;
    padding: 0 1rem;
    text-align: left;
  }
</style>

<!-- PHOTO DE PROFIL AU-DESSUS DE LA COVER -->
<div class="profile-wrapper">
  <div class="profile-photo">
    <img src="photo_jeco.jpg" alt="profile photo">
    <div class="profile-name">Etienne de L'Estoile</div>
  </div>
</div>

<!-- COVER EN-DESSOUS -->
<div class="cover-photo">
  <img src="torres_garcia_ciudad.jpg" alt="Cover image">
</div>

<!-- DESCRIPTION SOUS LA COVER -->
<div class="profile-description">
  <p><strong>Climate & Macroeconomics Economist</strong></p>
  <p>Macroprudential Policy and Financial Stability Division, Banque de France</p>
  <p>PhD in Economics, Paris 1 Panthéon-Sorbonne</p>
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
