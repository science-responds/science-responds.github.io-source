---
title: Events
permalink: /resources/events
---

{% include get_event_list.html %}

### Conferences and workshops
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