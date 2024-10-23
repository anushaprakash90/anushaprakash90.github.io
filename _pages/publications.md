---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">Selected and recent publications are given below. The complete list of my articles are available on <a href="https://scholar.google.com/citations?user=2r9mCcgAAAAJ&sortby=pubdate">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
