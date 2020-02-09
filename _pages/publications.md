---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


You can find a comprehensive list of my publications on <u><a href="https://scholar.google.it/citations?user=gYzXaPQAAAAJ" target="_blank">Google Scholar</a></u> or <u><a href="https://dblp.uni-trier.de/pers/hd/d/Dacrema:Maurizio_Ferrari" target="_blank">DBLP</a></u>.


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
