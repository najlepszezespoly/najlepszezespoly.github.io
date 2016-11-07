---
layout: page
title: kapele
---
<ul>
{% for item in site.data.kapele%}
<li style="{% if item.IsNow %}color: green {%endif%}">
    <em>   {{ item.name }} </em> {{item.IsNow}}  {{item.Price}}
  </li>
{% endfor %}
</ul>
