---
layout: default
title: "About me"
---
I am a Ph.D. candidate in Sociology at Nuffield College and the Department of Sociology at the University of Oxford. 


{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}