---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Complete list of all my publications can be found [here](https://orcid.org/my-orcid?orcid=0000-0003-4473-7242).

<hr style="height:0.3px;border:none;color:gray;background-color:gray;" />

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
