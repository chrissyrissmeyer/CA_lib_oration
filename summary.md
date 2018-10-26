---
title: Summary
---
# Summary

{% for item in site.data.object_properties %}
<h3>{{item.predicagte}}</h3>
{% for item in site.data.object_properties %}
<p>{{item.definition}}</p>
{% endfor %}
