---
layout: page
title: Member
---
{% include JB/setup %}

{% for category in site.categories %}
  <h4 id="{{ category[0]  }}-ref">{{ category[0] | join: "/"  }}</h4>
  <ul>
    {% assign pages_list = category[1] %}
    {% include JB/pages_list %}
  </ul>
{% endfor %}

