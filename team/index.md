---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our lab is a collaborative, supportive, and ambitious research community. We believe that diverse teams do better science, and strive to create an environment with transparent expectations and thoughtful mentorship, where researchers from different backgrounds can thrive. Our team will include postdoctoral associates, PhD, master's, and undergraduate students, postgraduate associates, research staff, and collaborators who share a commitment to rigorous, open, and inclusive science. Interested in joining the lab? Visit the [Join page]({{ "/join/" | relative_url }}) for information on how to apply.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}
