---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}
{% include base_path %}
## Preprints
{% for post in site.pubP reversed %}
  {% include archive-single-pub-cv.html %}
{% endfor %}
## Conference/Workshop Papers
{% for post in site.pubC reversed %}
  {% include archive-single-pub-cv.html %}
{% endfor %}
## Journal Papers
{% for post in site.pubJ reversed %}
  {% include archive-single-pub-cv.html %}
{% endfor %}
