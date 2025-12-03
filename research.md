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
    background-image: url('map_transparent.png'); /* <-- ton image */
    background-size: cover;
    background-position: center;
    padding: 6rem 1.5rem 4rem 1.5rem;
    margin-top: 3.5rem; /* pour dégager la top bar */
  }

  .research-overlay {
    position: absolute;
    inset: 0;
    background: rgba(246,239,230,0.78); /* beige semi-transparent */
    backdrop-filter: blur(2px);          /* très léger flou */
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

## Working Papers

- **Who Takes the Land?**  
  Quantifying built-up land use and land-take by French economic sectors (2008–2021).

- **Container or Content: Flood Hazards and Credit Risk**  
  A multi-country Digital Twin linking physical hazard maps, real estate assets,  
  and firm-balance-sheet data.

---

## Research Projects

### Climate–Macro Digital Twin
A scalable system combining hazard maps, exposure data, and financial networks  
to assess climate-related solvency impacts.

### Commercial Real Estate Indices for France
Hedonic transaction-based indices documenting CRE price trends and  
non-prime market dynamics.

### Land-Use & Land-Take Accounts
Geospatial accounts for all French economic sectors, informing  
“No Net Land Take” policies.

  </div>
</div>
