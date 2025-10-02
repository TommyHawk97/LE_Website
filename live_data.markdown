---
layout: page
title: Data
---
Testing Jekyll to show data from a CSV file.
<!--Lists all members of github on the page, the code below will list members from the csv file -->
<ul>
{% for member in site.data.csv_test %}
  <li>
    
    {{ member.deviceID }} {{member.voltage}}V
    
  </li>
{% endfor %}
</ul>
Testing Jekyll to show data from a TSV file.
<!--Code below will list the data from the tsv file-->
<ul>
{% for user in site.data.tsv_test %}
  <li>
    
    {{user.deviceID }} {{user.voltage}}V
    
  </li>
{% endfor %}
</ul>
