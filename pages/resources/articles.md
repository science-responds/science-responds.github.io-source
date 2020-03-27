---
title: Articles
permalink: /resources/articles
---

{% include get_pub_list.html %}

### Related academic papers
<ul>
{% assign pubs = sorted_publications | where: "type", "publication" %}
{% for pub in pubs %}
<li> {% include print_pub.html pub=pub %} </li>
{% endfor %}
</ul>

### Other related articles

<ul>
{% assign pubs = sorted_publications | where: "type", "article" %}
{% for pub in pubs %}
<li> {% include print_pub.html pub=pub %} </li>
{% endfor %}
</ul>
