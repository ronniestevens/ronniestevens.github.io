---
layout: default
permalink: /portfolio/
type: page
---
# Portfolio
{% for page in site.portfolio %}
    {{ page.title }}
{% endfor %}