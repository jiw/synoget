# Welcome to SynoGet!

## Article List

{% for page in site.pages %}
{% if page.title %}
- [{{ page.title }}]({{ page.url | relative_url }})
{% endif %}
{% endfor %}
