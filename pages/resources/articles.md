---
title: Articles
permalink: /resources/articles
---

{%- include get_pub_list.html -%}
{%- include get_article_list.html -%}
{%- include get_collection_list.html -%}

### Related publicaton lists
<ul>
{% for coll in sorted_collections %}
<li> {% include print_coll.html coll=coll %} </li>
{% endfor %}
</ul>

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
