---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true

---

<!-- You can also find my articles on my [Google Scholar profile](https://scholar.google.com/citations?user=j5Nqyc4AAAAJ&hl=en).-->
 
{% if author.googlescholar %}

 {% endif %}
 
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
