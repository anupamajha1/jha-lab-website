---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact Us

Our lab is part of the Yale School of Medicine's Department of Genetics. We are headquartered on the third floor of the Sterling Hall of Medicine.

{%
  include button.html
  type="email"
  text="anupama.jha@yale.edu"
  link="anupama.jha@yale.edu"
%}
{%
  include button.html
  type="phone"
  text="(203) 737-1081"
  link="+1-203-737-1081"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/XkvoRFJmKwEVkDSS9"
%}

{% include section.html %}

<div class="contact-media">
  <div class="contact-media-card">
    {% include figure.html image="images/jhalab_background.jpg" caption="Sterling Hall of Medicine" %}
  </div>
  <div class="contact-media-card">
    <figure class="figure">
      <div class="contact-map-frame">
        <iframe
          src="https://www.google.com/maps?q=333+Cedar+Street,+New+Haven,+CT+06510&z=16&output=embed"
          title="Map showing 333 Cedar Street, New Haven, CT 06510"
          loading="lazy"
          referrerpolicy="no-referrer-when-downgrade"
        ></iframe>
      </div>
      <figcaption class="figure-caption">333 Cedar Street, New Haven, CT 06510</figcaption>
    </figure>
  </div>
</div>
