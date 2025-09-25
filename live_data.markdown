---
layout: page
title: Data
---
Testing Jekyll to show data from a csv file.
<!--Lists all members of github on the page -->
<ul>
{% for member in site.data.csv_test %}
  <li>
    
    {{ member.name }}, {{member.github}}
    
  </li>
{% endfor %}
</ul>
