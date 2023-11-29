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
<ol reversed>{% for post in site.pubP reversed %}
  {% include archive-single-pub-cv.html %}
{% endfor %}</ol>
## Conference/Workshop Papers
<ol reversed>{% for post in site.pubC reversed %}
  {% include archive-single-pub-cv.html %}
{% endfor %}</ol>
## Journal Papers
<ol reversed>{% for post in site.pubJ reversed %}
  {% include archive-single-pub-cv.html %}
{% endfor %}</ol>
