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

We are looking for postdoctoral researchers, postgraduate associates, and PhD students who are excited about gene regulation, genome architecture, and machine learning.

**Interested in joining the lab?** Visit the [Join page]({{ "/contact/" | relative_url }}) for information on opportunities and how to apply.

{% endcapture %}

{%
  include feature.html
  image="images/jhalab_background.jpg"
  title="We are recruiting!"
  text=text
%}

{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="publications"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="publications"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
