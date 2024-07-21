---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">Please see all my publications on <a href="{{site.author.googlescholar}}"> Google Scholar profile</a>.</div>
{% endif %}

The following are some of my recent research outcomes:

[Design Drinciples for Demand-responsive Railway Station Areas] (http://c1309928130.pythonanywhere.com/?dimension=All


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
