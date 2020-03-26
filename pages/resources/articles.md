---
title: Articles
permalink: /resources/articles
---

{% include get_pub_list.html %}

### Related academic papers
<ul>
  {% for pub in sorted_publications %}
     {% if pub.type == 'publication' %}
     <li> {% include print_pub.html pub=pub %} </li>
     {% endif %}
  {% endfor %}
</ul>

### Other related articles

<ul>
  {% for pub in sorted_publications %}
     {% if pub.type == 'article' %}
     <li> {% include print_pub.html pub=pub %} </li>
     {% endif %}
  {% endfor %}
</ul>
