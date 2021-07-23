---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Song, Yongjia, Abimael Hernandez Jimenez, and Gregory Scontras. 2021. Cross-linguistic scope ambiguity:
An investigation of English, Spanish, and Mandarin. Proceedings of the Linguistic Society of
America 6, 572-586. [Paper]

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
