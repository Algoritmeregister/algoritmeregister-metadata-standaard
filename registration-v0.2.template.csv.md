---
permalink: registration-v0.2.template.csv
---
{% for property in site.data.schema-v0_2.properties %}{{ property.attribute }}{% if forloop.last == false %},{% endif %}{% endfor %}