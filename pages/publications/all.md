---
permalink: /pubs.html
layout: main
title: Publications
draft: false
---

## Related publications 

{% include get_pub_list.html %}

### Academic papers
<ul>
  {% for pub in sorted_publications %}
     {% if pub.article == "article" %}
     <li> {% include print_pub.html pub=pub %} </li>
     {% endif %}
  {% endfor %}
</ul>

### Other articles

<ul>
  {% for pub in sorted_publications %}
     {% if pub.article != "article" %}
     <li> {% include print_pub.html pub=pub %} </li>
     {% endif %}
  {% endfor %}
</ul>
