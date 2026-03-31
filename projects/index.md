---
title: Research
nav:
  order: 1
  tooltip: Research directions and methods
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

<div class="research-page">
  <p class="research-lead">
    We build interpretable machine learning models to understand how DNA sequence and 3D genome architecture shape gene regulation across healthy tissues, mammalian evolution, and cancer.
  </p>

  <div class="research-intro">
    <p>
      Our work sits at the intersection of genomics, RNA biology, and machine learning. We integrate Hi-C, ATAC-seq, RNA-seq, long-read chromatin assays, and comparative genomics to study how nuclear organization influences transcription, splicing, and cellular identity. Across this program, we aim to uncover the sequence rules of genome folding, model how chromatin architecture impacts downstream regulation, and identify when these regulatory systems break in disease.
    </p>
    <p>
      This research program grows directly out of my previous work in interpretable models of RNA splicing, long-read epigenomic tool building, and sequence-to-function prediction of chromosomal contacts. Together, these directions define a broader agenda: using AI to connect genome sequence to structure, and structure to function.
    </p>
  </div>

  {% include button.html text="See our publications" link="/publications/" style="home-cta" %}

  {% include section.html %}

  <div class="research-talks">
    <h2>Research Talks</h2>
    <p class="research-talks-intro">
      These talks give a short introduction to the kinds of questions, models, and datasets that motivate the lab.
    </p>
    <div class="video-grid">
      <div class="video-card">
        <div class="video-frame">
          <iframe
            src="https://www.youtube.com/embed/WPf9hqXJLIU"
            title="MLCB 2023 talk"
            loading="lazy"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            referrerpolicy="strict-origin-when-cross-origin"
            allowfullscreen
          ></iframe>
        </div>
        <p class="video-caption">One-minute research talk from MLCB 2023</p>
      </div>
      <div class="video-card">
        <div class="video-frame">
          <iframe
            src="https://www.youtube.com/embed/eHwMlYv-wlE"
            title="ISMB ECCB 2023 talk"
            loading="lazy"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            referrerpolicy="strict-origin-when-cross-origin"
            allowfullscreen
          ></iframe>
        </div>
        <p class="video-caption">Conference talk on modeling 3D genome architecture and regulation</p>
      </div>
    </div>
  </div>

  {% include section.html %}

  <h2>Research Areas</h2>

  <div class="research-arm">
    <div class="research-arm-image">
      <img src="{{ 'images/figure_research_statement.png' | relative_url }}" alt="Overview of sequence, chromatin architecture, and gene regulation">
    </div>
    <div class="research-arm-text">
      <h3>Modeling how 3D genome architecture regulates gene expression and splicing</h3>
      <p>
        A central goal of the lab is to understand how chromatin interactions shape transcriptional output and isoform regulation across tissues. We are developing sequence-to-function models that combine DNA sequence, chromatin accessibility, and 3D genome organization to predict transcriptional and post-transcriptional regulation in human cells.
      </p>
      <p>
        These models are designed to move beyond promoter-proximal prediction and capture how distal regulatory interactions influence tissue-specific gene regulation in both healthy and disease contexts.
      </p>
    </div>
  </div>

  <div class="research-arm" data-flip="true">
    <div class="research-arm-image">
      <img src="{{ 'images/twinc.jpg' | relative_url }}" alt="TwinC figure for predicting chromatin contacts from sequence">
    </div>
    <div class="research-arm-text">
      <h3>Learning the sequence rules of genome folding</h3>
      <p>
        We develop predictive models of chromatin contacts to identify the sequence determinants of nuclear organization. Building on TwinC and related work, we study both cis and trans contacts across human tissues to reveal the motifs and sequence features that help establish large-scale 3D genome structure.
      </p>
      <p>
        This direction also opens the door to variant interpretation: predicting how SNPs, indels, and structural variants alter nuclear architecture and, in turn, gene regulation.
      </p>
    </div>
  </div>

  <div class="research-arm">
    <div class="research-arm-image">
      <img src="{{ 'images/evo2hic_figure.png' | relative_url }}" alt="Cross-species modeling of genome architecture">
    </div>
    <div class="research-arm-text">
      <h3>Comparative and multimodal models of chromatin architecture</h3>
      <p>
        We are interested in what genome organization is conserved across mammalian evolution and what that conservation reveals about regulatory function. By integrating sequence, Hi-C, accessibility, and multimodal foundation-model representations, we aim to derive structure-aware measures of conservation and identify regulatory elements shaped by both sequence and 3D context.
      </p>
      <p>
        These comparative models help us ask not only how genomes fold, but which aspects of folding are stable, functional, and predictive across species and cell types.
      </p>
    </div>
  </div>

  <div class="research-arm" data-flip="true">
    <div class="research-arm-image">
      <img src="{{ 'images/cancer-signatures.jpg' | relative_url }}" alt="Cancer gene regulation and transcriptomic dysregulation">
    </div>
    <div class="research-arm-text">
      <h3>Discovering genome-structure mechanisms of gene misregulation in cancer</h3>
      <p>
        We use large-scale genomic and transcriptomic data to study how cancer rewires genome organization and downstream gene regulation. This includes identifying chromatin and sequence variants associated with altered expression and splicing programs, and building models that connect aberrant 3D structure to shared cancer phenotypes.
      </p>
      <p>
        Our long-term goal is to define which sequence and structural alterations drive gene misregulation in tumors and to make those mechanisms predictable from genomic data.
      </p>
    </div>
  </div>

  {% include section.html %}
</div>
