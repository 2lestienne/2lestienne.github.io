---
title: "Research"
layout: default
---

<style>
  html, body {
    margin: 0;
    padding: 0;
  }
  body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    background: #f6efe6;
    line-height: 1.6;
    color: #222;
  }

  /* TOP BAR — identique à index */
  .top-bar {
    position: absolute;
    top: 0;
    left: 50%;
    right: 50%;
    width: 100vw;
    margin-left: -50vw;
    margin-right: -50vw;
    background: rgba(246,239,230,0.92);
    border-bottom: 1px solid #e0d4c5;
    padding: 0.6rem 0;
    z-index: 30;
  }
  .top-bar-inner {
    max-width: 1200px;
    margin: auto;
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

  /* SECTION RESEARCH AVEC IMAGE DE FOND */
.research-section {
  position: relative;
  background-image: url('/buildings_floods_EN.png');
  background-size: cover;
  background-position: center;
  padding: 4.5rem 1.5rem 4rem 1.5rem; /* réduit un peu le padding haut */
  margin-top: 0;                     /* enlève l'espace ! */
}


  .research-overlay {
    position: absolute;
    inset: 0;
    background: rgba(246,239,230,0.60); /* beige semi-transparent */
    backdrop-filter: blur(1px);          /* très léger flou */
    z-index: 1;
  }

  .research-text {
    position: relative;
    z-index: 2;
    max-width: 900px;
    margin: auto;
    background: transparent;
    padding: 1rem 0;
  }

  /* TITRES */
  h1, h2, h3 {
    color: #5d3a23;
    margin-top: 1.5rem;
  }

</style>

<div class="top-bar">
  <div class="top-bar-inner">
    <div class="site-name">Etienne de L'Estoile</div>
    <nav class="site-nav">
      <a href="/">About me</a>
      <a href="/vita">Vita</a>
      <a href="/research">Research</a>
      <a href="/outreach">Outreach</a>
      <a href="/writing">Writing</a>
    </nav>
  </div>
</div>

<!-- SECTION AVEC L'IMAGE EN FOND -->
<div class="research-section">
  <div class="research-overlay"></div>

  <div class="research-text" markdown="1">

# Research

My work focuses on the empirical modelling of **climate risks**, **physical hazards**,  
and **macro-financial stability**, using high-resolution spatial data, firm-level microdata,  
and geospatial Digital Twin architectures.

---

## Publications 
- **[Digital twins for bridging climate data gaps: from flood hazards to firms’ physical assets to banking risks](https://www.bis.org/ifc/publ/ifcb63_10.pdf){:target="_blank"}** (2025)
With [Lisa Kerdelhué](https://www.banque-france.fr/fr/lisa-kerdelhue){:target="_blank"} and Thierry Verdier

## Working Papers

- **[Who Takes the Land? Quantifying the Use of Built-Up Land by French Economic Sectors to Assess Their Vulnerability to the ‘No Net Land Take’ Policy](https://www.banque-france.fr/en/publications-and-statistics/publications/who-takes-land-quantifying-use-built-land-french-economic-sectors-assess-their-vulnerability-no-net){:target="_blank"}** (2024)
With [Mathilde Salin](https://www.banque-france.fr/fr/mathilde-salin){:target="_blank"}
<p style="font-size:0.9rem;">
We construct the first sector-level accounts of built-up land use and land take in France (2008–2021), combining geospatial and administrative microdata on firms. We find that economic sectors have highly unequal land footprints, revealing differentiated vulnerabilities to the “no net land take” policy.
</p>


- **[Container or Content: from flood hazards on firms’ physical assets to credit risks](https://www.banque-france.fr/en/publications-and-statistics/publications/who-takes-land-quantifying-use-built-land-french-economic-sectors-assess-their-vulnerability-no-net){:target="_blank"}** (2025)
With [Lisa Kerdelhué](https://www.banque-france.fr/fr/lisa-kerdelhue){:target="_blank"} and Thierry Verdier  
<p style="font-size:0.9rem;">
  Development of a multi-country Digital Twin integrating physical hazard maps, firm-level financial statements, and real-estate exposures to quantify damages and solvency effects for firms and banks. 
</p>


---

## Selected Research Projects

- **Commercial Property Price Indices for France**
<p style="font-size:0.9rem;">
Construction of the first public transaction-based commercial real estate indices for France using millions of DV3F property transactions and hedonic modelling. The project sheds light on price dynamics, non-prime segments, and financial stability implications.
</p>

- **REITs and natural catastrophes**

- **Natural catastrophes and loan standards**





  </div>
</div>
