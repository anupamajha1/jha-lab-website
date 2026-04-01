---
title: Home
nav:
  order: 0
  tooltip: Back to homepage
---

# Welcome to the Jha Lab at Yale Genetics!

<p style="text-align: center;">
We study 3D genome architecture and gene regulation in healthy tissues and cancer using machine learning.
</p>

{% include section.html %}

{% capture text %}

We are looking for postdoctoral associates, research staff, postgraduate associates, and PhD students who are excited about gene regulation, genome architecture, and machine learning.

**Interested in joining the lab?** Please reach out to anupama[dot]jha[at]yale[dot]edu with your CV and a brief description of your research interests.

{% endcapture %}

{%
  include feature.html
  image="images/jhalab_background.jpg"
  title="We are hiring!"
  text=text
  dark=true
%}

{% include section.html %}

## Highlights

{% capture text %}

We develop interpretable machine learning methods to predict genome architecture and gene regulation from sequence and genomic data.

{%
  include button.html
  link="publications"
  text="See our research"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="home-cta"
%}

{% endcapture %}

{%
  include feature.html
  image="images/figure_research_statement.png"
  link="publications"
  title="AI in Biology"
  text=text
  contain=true
%}

{% capture text %}

Explore recent publications spanning 3D genome architecture, RNA splicing, long-read epigenomics, and interpretable machine learning.

{%
  include button.html
  link="publications"
  text="Browse our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="home-cta"
%}

{% endcapture %}

{%
  include feature.html
  image="images/publications_image.png"
  link="publications"
  title="Publications"
  flip=true
  style="bare"
  text=text
  contain=true
%}

{% capture text %}

Meet the researchers building computational methods to understand genome regulation across healthy tissues and disease.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="home-cta"
%}

{% endcapture %}

{%
  include feature.html
  image="images/jhalab_background.jpg"
  link="team"
  title="Our Team"
  text=text
%}
