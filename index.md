---
title: "Etienne de L'Estoile"
description: "Climate & Macrofinance Economist – Financial Stability, Climate Risk, Real Estate"
layout: default
---

<style>
  /* Supprimer marges par défaut */
  body > *:first-child {
    margin-top: 0 !important;
    padding-top: 0 !important;
  }

  html, body {
    margin: 0;
    padding: 0;
  }

  .page-content,
  .wrapper,
  .site,
  .site-main,
  .post-content,
  .home {
    background: transparent !important;
  }

  body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    line-height: 1.6;
    background:#f6efe6;
    color: #222222;
  }

  /* ===== HEADER : COVER + TOP BAR ===== */

  .header-wrapper {
    position: relative;
    margin: 0;
    padding: 0;
  }

  .cover-photo {
    position: relative;
    margin: 0;
    padding: 0;
    z-index: 1;
    width: 100vw;
    overflow: hidden;
    background: #2b1a12;
    left: 50%;
    right: 50%;
    margin-left: -50vw;
    margin-right: -50vw;
  }

  .cover-photo img {
    width: 100%;
    height: auto;
    display: block;
  }

  .top-bar {
    position: absolute;
    top: 0;
    left: 50%;
    right: 50%;
    width: 100vw;
    margin-left: -50vw;
    margin-right: -50vw;
    z-index: 30;

    background: rgba(246,239,230,0.92);
    border-bottom: 1px solid #e0d4c5;
    box-sizing: border-box;
    padding: 0.6rem 0;
  }

  .top-bar-inner {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 1.2rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .site-name {
    font-size: 1.2rem;
    font-weight: 600;
    color: #5d3a23;
    margin: 0;
  }

  .site-nav a {
    margin-left: 1rem;
    text-decoration: none;
    color: #5d3a23;
    font-weight: 500;
  }

  .site-nav a:hover {
    text-decoration: underline;
  }

  /* ===== LAYOUT 2 COLONNES ===== */

  .main-layout {
    max-width: 900px;
    margin: 0 auto 3rem auto;   /* pas remonté : la sidebar seule chevauche */
    padding: 0 1rem;
    display: flex;
    gap: 2rem;
    align-items: flex-start;
  }

  /* Colonne gauche */
  .sidebar {
    width: 230px;
    flex-shrink: 0;
    margin-top: -85px;  
     position: relative;
    z-index: 20;  /* chevauchement de la cover */
  }

  .sidebar-photo {
    width: 180px;
    height: 180px;
    object-fit: cover;
    border-radius: 6px;
    border: 4px solid #f6efe6;
    box-shadow: 0 2px 10px rgba(0,0,0,0.15);
    margin-bottom: 0.75rem;
  }

  .sidebar-name {
    font-size: 1.25rem;
    font-weight: 600;
    color:#5d3a23;
    margin-bottom: 0.4rem;
  }

  .sidebar-title {
    font-size: 0.95rem;
    margin-bottom: 0.8rem;
    line-height: 1.4;
  }

  .sidebar-title strong {
    font-size: 1rem;
  }

  .sidebar-links {
    font-size: 0.9rem;
  }

  .sidebar-links a {
    display: block;
    text-decoration: none;
    color: #5d3a23;
    margin-bottom: 0.3rem;
  }

  .sidebar-links a:hover {
    text-decoration: underline;
  }

  /* Colonne droite : About Me */
  .content {
    flex: 1;
    max-width: none;
    margin: 30px 0 0 0;      /* commence plus bas que la photo */
    padding: 0 0 3rem 0;
    background: transparent;
    box-shadow: none;
    border-radius: 0;
  }

  .content h1,
  .content h2,
  .content h3 {
    color:#5d3a23;
  }

  /* ===== Responsive ===== */

  @media (max-width: 800px) {
    .main-layout {
      flex-direction: column;
      margin-top: 1.5rem;
    }

    .sidebar {
      width: 100%;
      margin-top: 0;            /* sur mobile, on ne chevauche plus */
      display: flex;
      gap: 1rem;
      align-items: flex-start;
    }

    .sidebar-photo {
      width: 140px;
      height: 140px;
    }

    .content {
      margin-top: 1.5rem;
    }
  }
</style>

<div class="header-wrapper">
  <div class="cover-photo">
    <img src="ciudad_garcia.jpg" alt="Cover image">
  </div>

  <div class="top-bar">
    <div class="top-bar-inner">
      <div class="site-name">Etienne de L'Estoile</div>

      <nav class="site-nav">
        <a href="/">About me</a>
        <a href="/vita">Vita</a>
        <a href="/research">Research</a>
        <a href="/outreach">Outreach</a>
      </nav>
    </div>
  </div>
</div>

<div class="main-layout">
  <!-- Colonne gauche -->
  <aside class="sidebar">
    <div>
      <img src="photo_jeco.jpg" alt="Etienne de L'Estoile" class="sidebar-photo">

      <div class="sidebar-name">Etienne de L'Estoile</div>

      <div class="sidebar-title">
        <strong>Climate &amp; Macrofinance Economist</strong><br>
        Banque de France<br>
        Paris 1 Panthéon-Sorbonne
      </div>

      <div class="sidebar-links">
        <a href="https://www.linkedin.com" target="_blank">LinkedIn</a>
        <a href="https://www.banque-france.fr/fr/etienne-de-lestoile" target="_blank">Banque de France profile</a>
        <a href="https://shs.cairn.info/publications-de-etienne-de-lestoile--699197?lang=fr" target="_blank">Cairn publications</a>
      </div>
    </div>
  </aside>

  <!-- Colonne droite : About Me -->
  <div class="content" markdown="1">

# About Me

I am an Economist in the Macroprudential Policy and Financial Stability Division at the Banque de France and hold a PhD in Economics from Paris 1 Panthéon-Sorbonne.  
My work focuses on the intersection of <strong>climate risks, macro-financial stability, and data-intensive modelling</strong>.

I develop empirical tools to quantify the exposure of real estate, firms and the financial system to environmental shocks, using high-resolution physical risk data, geospatial information, and granular balance-sheet microdata. My research is applied, policy-relevant, and aims to inform regulators and investors about emerging climate vulnerabilities.

---

## Research Interests

- Climate–macro linkages and environmental shocks  
- Natural disaster impacts & physical risk modelling  
- Macroprudential policy & financial stability  
- Real estate & land-use economics  

</div>
