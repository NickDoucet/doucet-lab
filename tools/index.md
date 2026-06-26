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
  object-fit: contain;
  border: 1px solid #ddd;
  margin-bottom: 18px;
  background: #fff;
}

.tool-card h3 {
  font-size: 1.05rem;
  text-align: center;
  margin-top: 0;
  margin-bottom: 18px;
  line-height: 1.45;
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

## Useful tools developed by the global protein engineering community

The links below are provided as a curated list of useful community resources for protein engineering and related fields. Inclusion on this page does not imply endorsement, ownership, or responsibility for external content. If you are the developer of a listed tool and would prefer that we remove or modify the link, please contact us and we will be happy to do so.

<div class="tool-grid">

  <div class="tool-card">
    <a href="https://spaseproteindesign.share.zrok.io/" target="_blank" rel="noopener">
      <img src="{{ site.baseurl }}/images/spase-logo-smaller.png" alt="SPASE protein design tool">
    </a>
    <h3><a href="https://spaseproteindesign.share.zrok.io/" target="_blank" rel="noopener">SPASE<br>Soluble Protein Analog Selection Engine</a></h3>
    <p>
      <strong>SPASE</strong> is a protein engineering pipeline built around <strong>ProteinMPNN</strong> as its core generative engine, combined with complementary biophysical filters. From a monomeric structure, it generates approximately 10,000 sequences, then filters them using Protein-Sol, ESMFold, and Aggrescan3D. It prioritizes stable, soluble, and expressible variants, with optional residue constraints to preserve function.
    </p>
  </div>

  <div class="tool-card">
    <a href="https://degradolab.org/suns/" target="_blank" rel="noopener">
      <img src="{{ site.baseurl }}/images/suns-logo-small-resized_orig.png" alt="Suns structural search engine">
    </a>
    <h3><a href="https://degradolab.org/suns/" target="_blank" rel="noopener">Suns<br>The Structural Search Engine</a></h3>
    <p>
      <strong>Suns</strong> is a structural search engine for protein databases that integrates with <strong>PyMOL</strong>. It enables users to build all-atom motif queries, find and align similar structures, and validate designed or modeled proteins against experimentally determined structures.
    </p>
  </div>

  <div class="tool-card">
    <a href="https://github.com/polizzilab/NISE" target="_blank" rel="noopener">
      <img src="{{ site.baseurl }}/images/niselogo_orig.png" alt="NISE protein design workflow">
    </a>
    <h3><a href="https://github.com/polizzilab/NISE" target="_blank" rel="noopener">Neural Iterative Selection Expansion<br>NISE</a></h3>
    <p>
      <strong>NISE</strong> is a protein design pipeline that generates sequences from structural backbones by iteratively combining sequence design and structure prediction, while enforcing ligand and geometric constraints to produce candidate proteins consistent with a target binding or structural objective.
    </p>
  </div>

  <div class="tool-card">
    <a href="https://loschmidt.chemi.muni.cz/aggreprot/" target="_blank" rel="noopener">
      <img src="{{ site.baseurl }}/images/aggreprot_orig.png" alt="AggreProt aggregation prediction server">
    </a>
    <h3><a href="https://loschmidt.chemi.muni.cz/aggreprot/" target="_blank" rel="noopener">AggreProt</a></h3>
    <p>
      <strong>AggreProt</strong> is a web server that uses deep convolutional neural networks to predict protein aggregation and engineer solubility. It provides per-residue and overall aggregation scores, incorporating solvent accessibility and transmembrane propensity. It is sequence-based, trained on amyloid hexapeptides, and mainly detects short amyloid-prone regions.
    </p>
  </div>

  <div class="tool-card">
    <a href="https://loschmidt.chemi.muni.cz/loopgrafter/#/" target="_blank" rel="noopener">
      <img src="{{ site.baseurl }}/images/loop-grafter-logo-28d69085_orig.png" alt="LoopGrafter protein loop grafting tool">
    </a>
    <h3><a href="https://loschmidt.chemi.muni.cz/loopgrafter/#/" target="_blank" rel="noopener">LoopGrafter</a></h3>
    <p>
      <strong>LoopGrafter</strong> provides guidance for transplanting loops between two structurally related proteins, defined as scaffold/source and insert/target, while assessing their dynamic properties. For best use, grafting is recommended on proteins that differ by no more than 8 Å RMSD and less than 20% of sequence length.
    </p>
  </div>

  <div class="tool-card">
    <a href="https://loschmidt.chemi.muni.cz/predictonco/" target="_blank" rel="noopener">
      <img src="{{ site.baseurl }}/images/predictonco_orig.png" alt="PredictONCO cancer mutation analysis tool">
    </a>
    <h3><a href="https://loschmidt.chemi.muni.cz/predictonco/" target="_blank" rel="noopener">PredictONCO</a></h3>
    <p>
      <strong>PredictONCO</strong> is a web tool for automated and fast analysis of the effects of mutations on stability and function in known cancer targets. It applies molecular modeling, bioinformatics, and machine learning approaches, and supports treatment-oriented analysis by evaluating mutation effects on binding to FDA- and EMA-approved drugs.
    </p>
  </div>

  <div class="tool-card">
    <a href="https://loschmidt.chemi.muni.cz/soluprotmutdb/" target="_blank" rel="noopener">
      <img src="{{ site.baseurl }}/images/soluprotmutdb_orig.png" alt="SoluProtMutDB protein solubility mutant database">
    </a>
    <h3><a href="https://loschmidt.chemi.muni.cz/soluprotmutdb/" target="_blank" rel="noopener">SoluProtMutDB</a></h3>
    <p>
      <strong>SoluProtMutDB</strong> is a curated database of protein solubility data for single- and multi-point mutants, compiled from published studies. It documents how mutations affect solubility and provides standardized, machine-learning-ready data to support protein engineering and the design of more soluble protein variants.
    </p>
  </div>

  <div class="tool-card">
    <a href="https://loschmidt.chemi.muni.cz/fireprotasr/" target="_blank" rel="noopener">
      <img src="{{ site.baseurl }}/images/fireprotasr_orig.png" alt="FireProtASR ancestral sequence reconstruction server">
    </a>
    <h3><a href="https://loschmidt.chemi.muni.cz/fireprotasr/" target="_blank" rel="noopener">FireProtASR</a></h3>
    <p>
      <strong>FireProtASR</strong> is a web server for automated ancestral sequence reconstruction from a single protein sequence. It builds homolog datasets, performs alignment, phylogenetic tree construction, and ancestral sequence inference with gaps. It supports both fully automated workflows and user-provided data at different pipeline stages.
    </p>
  </div>

  <div class="tool-card">
    <a href="https://loschmidt.chemi.muni.cz/caverweb/" target="_blank" rel="noopener">
      <img src="{{ site.baseurl }}/images/caverweb_orig.png" alt="CAVER Web tunnel and channel analysis server">
    </a>
    <h3><a href="https://loschmidt.chemi.muni.cz/caverweb/" target="_blank" rel="noopener">CAVER Web 1.0</a></h3>
    <p>
      <strong>CAVER Web</strong> is an interactive server for analyzing protein tunnels, channels, and ligand transport. It integrates CAVER for tunnel detection and CaverDock for transport simulation, with guided setup for users. It supports multiple ligand inputs and provides fast, accurate results with moderate computation time.
    </p>
  </div>

  <div class="tool-card">
    <a href="https://loschmidt.chemi.muni.cz/soluprot/" target="_blank" rel="noopener">
      <img src="{{ site.baseurl }}/images/soluprot_orig.png" alt="SoluProt protein solubility prediction server">
    </a>
    <h3><a href="https://loschmidt.chemi.muni.cz/soluprot/" target="_blank" rel="noopener">SoluProt 1.0</a></h3>
    <p>
      <strong>SoluProt</strong> is a web application that predicts protein solubility from amino acid sequence using a random forest model with 36 sequence-derived features. It generates a solubility score to prioritize experimental protein production and is trained on physicochemical, structural, and homology-based descriptors.
    </p>
  </div>

  <div class="tool-card">
    <a href="https://loschmidt.chemi.muni.cz/enzymeminer/" target="_blank" rel="noopener">
      <img src="{{ site.baseurl }}/images/enzymeminer_orig.png" alt="EnzymeMiner sequence mining web application">
    </a>
    <h3><a href="https://loschmidt.chemi.muni.cz/enzymeminer/" target="_blank" rel="noopener">EnzymeMiner 1.0</a></h3>
    <p>
      <strong>EnzymeMiner</strong> is a web application that automatically mines genomic databases for enzyme sequences with conserved catalytic residues. It integrates sequence and structural bioinformatics, including structure prediction, cavity and tunnel analysis, and enzyme–substrate modeling, to identify and assess functionally diverse candidates for a defined enzymatic reaction.
    </p>
  </div>

  <div class="tool-card">
    <a href="https://loschmidt.chemi.muni.cz/calfitter/" target="_blank" rel="noopener">
      <img src="{{ site.baseurl }}/images/calfitter_orig.png" alt="CalFitter differential scanning calorimetry fitting tool">
    </a>
    <h3><a href="https://loschmidt.chemi.muni.cz/calfitter/" target="_blank" rel="noopener">CalFitter 2.0</a></h3>
    <p>
      <strong>CalFitter</strong> is a tool for analyzing and fitting protein melting curves from differential scanning calorimetry data. It supports global fitting across scan rates and reheating using multiple unfolding models, and outputs intermediate populations, fitted parameters with confidence intervals, and results exportable to Excel.
    </p>
  </div>

</div>

## Click here to access the 6th PEC Conference website

<div class="tools-hero">
  <a href="https://event.fourwaves.com/pec2026/pages" target="_blank" rel="noopener">
    <img src="{{ site.baseurl }}/images/pec-banner.png" alt="Protein Engineering Canada conference banner">
  </a>
</div>

{% include section.html %}
