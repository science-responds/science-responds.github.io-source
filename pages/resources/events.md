---
title: Events
permalink: /resources/events
---

{% include get_event_list.html %}

### Seminars, discussions, conferences and workshops
<ul>
  {% for evt in sorted_events %}
     {% if evt.type == 'conference' %}
     <li> {% include print_evt.html evt=evt %} </li>
     {% endif %}
  {% endfor %}
</ul>


### Hackathons
<ul>
  {% for evt in sorted_events %}
     {% if evt.type == 'hackathon' %}
     <li> {% include print_evt.html evt=evt %} </li>
     {% endif %}
  {% endfor %}
</ul>

### Courses
<ul>
  {% for evt in sorted_events %}
     {% if evt.type == 'course' %}
     <li> {% include print_evt.html evt=evt %} </li>
     {% endif %}
  {% endfor %}
</ul>

### Other events

<ul>
  {% for evt in sorted_events %}
     {% if evt.type != 'conference' %}
     {% if evt.type != 'hackathon' %}
     {% if evt.type != 'course' %}
     <li> {% include print_evt.html evt=evt %} </li>
     {% endif %}
     {% endif %}
     {% endif %}
  {% endfor %}
</ul>


{% assign currentdatecmp = 'now' | date: "%s" %}
{% assign i = 0 %}
{% for evt in sorted_events %}
   {{ evt.highlight }} 
   {{ evt.date }}
   {% if evt.highlight == 'yes' %}
   {% assign t_date = evt.date | date: "%s" %}
   {{ evt.date }} 
   {{ t_date }}
   {% if t_date >= currentdatecmp %} 
    {% increment i %}
   {% endif %}
   {% endif %}
{% endfor %}

Test area
{{ currentdatecmp }}
{{ i }}
{{ t_date }}

{% if i > 0 %}
### Upcoming highlights
<ul>
  {% for evt in sorted_events %}
     {% if evt.highlight == 'yes' %}
     {% assign t_date = evt.date | date: "%s" %}
     {% if t_date >= currentdatecmp %}      
       <li> {% include print_evt.html evt=evt %} </li>
     {% endif %}
     {% endif %}
  {% endfor %}
</ul>
{% endif %}
