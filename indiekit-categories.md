---
layout: null
permalink: categories.json
---
{
    "categories": [{% for category in site.tags %}
      "{{ category }}"{% unless forloop.last %},{% endunless %}{% endfor %}
    ]
}