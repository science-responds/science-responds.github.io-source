---
title: Articles
permalink: /resources/articles
---

{%- include get_pub_list.html -%}
{%- include get_article_list.html -%}

### Related academic papers
<ul>
{% for pub in sorted_publications %}
<li> {% include print_pub.html pub=pub %} </li>
{% endfor %}
</ul>

### Related articles

<ul>
{% for pub in sorted_articles %}
<li> {% include print_pub.html pub=pub %} </li>
{% endfor %}
</ul>
