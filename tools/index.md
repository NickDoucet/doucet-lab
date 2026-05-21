---
title: Tools
nav:
  order: 3
  tooltip: Software, servers, and resources
---

# {% include icon.html icon="fa-solid fa-screwdriver-wrench" %} Protein Engineering Canada Portal

The Protein Engineering Community brings together computational tools, structural biology workflows, and analytical pipelines that support protein design, biomolecular characterization, and systems research. Some of these resources are featured below. If you have developed a relevant tool or workflow and would like it linked here, we would be happy to hear from you.

{% include section.html %}

<style>
.tools-hero {
  margin: 20px 0 60px 0;
}

.tools-hero img {
  width: 100%;
  max-height: 280px;
  object-fit: cover;
  border-radius: 6px;
  box-shadow: 0 4px 18px rgba(0,0,0,0.12);
}

.tool-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 32px;
  margin-top: 35px;
}

.tool-card {
  border: 1px solid #ddd;
  background: #fff;
  padding: 18px;
  border-radius: 4px;
  box-shadow: 0 3px 12px rgba(0,0,0,0.05);
  transition: transform 0.15s ease, box-shadow 0.15s ease;
}

.tool-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 6px 18px rgba(0,0,0,0.10);
}

.tool-card img {
  width: 100%;
  height: 230px;
  object-fit: cover;
  border: 1px solid #ddd;
  margin-bottom: 18px;
}

.tool-card h3 {
  font-size: 1.05rem;
  text-align: center;
  margin-top: 0;
  margin-bottom: 18px;
}

.tool-card h3 a {
  color: inherit;
  text-decoration: underline;
}

.tool-card p {
  font-size: 0.95rem;
  line-height: 1.65;
  text-align: justify;
}

@media (max-width: 900px) {
  .tool-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 600px) {
  .tool-grid {
    grid-template-columns: 1fr;
  }
}
</style>

## Protein engineering resources

<div class="tools-hero">
  <a href="https://event.fourwaves.com/pec2026/pages">
    <img src="{{ site.baseurl }}/images/pec-banner.png" alt="Protein Engineering Canada conference banner">
  </a>
</div>

{% include section.html %}

## Tools developed by our community

<div class="tool-grid">

  <div class="tool-card">
    <img src="{{ site.baseurl }}/images/tools/spase.jpg" alt="SPASE protein design tool">
    <h3><a href="https://proteinengineering.ca">SPASE<br>Soluble Protein Analog Selection Engine</a></h3>
    <p>
      SPASE is a protein engineering pipeline built around <strong>ProteinMPNN</strong> as its core generative engine, combined with complementary biophysical filters for solubility, aggregation propensity, and structural preservation.
    </p>
  </div>

  <div class="tool-card">
    <img src="{{ site.baseurl }}/images/tools/suns.jpg" alt="Suns structural search engine">
    <h3><a href="#">Suns<br>The Structural Search Engine</a></h3>
    <p>
      Suns is a structural search engine for protein databases that integrates with PyMOL. It enables users to build all-atom motif queries, find and align similar structures, and validate designed or modeled proteins against experimentally determined structures.
    </p>
  </div>

  <div class="tool-card">
    <img src="{{ site.baseurl }}/images/tools/nise.jpg" alt="NISE protein design workflow">
    <h3><a href="#">Neural Iterative Selection Expansion<br>NISE</a></h3>
    <p>
      NISE is a protein design workflow that combines sequence design, structure prediction, and iterative selection to generate candidate protein variants while enforcing ligand, geometric, or functional constraints.
    </p>
  </div>

  <div class="tool-card">
    <img src="{{ site.baseurl }}/images/tools/pymol.jpg" alt="PyMOL scripts">
    <h3><a href="#">PyMOL visualization scripts</a></h3>
    <p>
      A collection of scripts and workflows for generating publication-quality molecular figures, highlighting active-site loops, ligand-binding regions, conformational changes, and protein engineering hotspots.
    </p>
  </div>

  <div class="tool-card">
    <img src="{{ site.baseurl }}/images/tools/nmr.jpg" alt="NMR analysis workflows">
    <h3><a href="#">NMR analysis workflows</a></h3>
    <p>
      Tools and protocols for NMR spectral analysis, biomolecular fingerprinting, titration mapping, and high-throughput characterization of proteins, ligands, and complex biological or food matrices.
    </p>
  </div>

  <div class="tool-card">
    <img src="{{ site.baseurl }}/images/tools/foodomics.jpg" alt="Foodomics and maple syrup characterization">
    <h3><a href="#">Foodomics and molecular fingerprinting</a></h3>
    <p>
      Analytical workflows combining NMR, chromatography, infrared spectroscopy, and chemometrics to classify maple syrup and other food matrices according to molecular composition, quality markers, and terroir-related signatures.
    </p>
  </div>

</div>
