---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find Supavit's articles on <u><a href="{{https://scholar.google.co.th/citations?hl=en&user=i4dWU4cAAAAJ&view_op=list_works&sortby=pubdate}}">his Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
