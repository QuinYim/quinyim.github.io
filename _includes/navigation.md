{% for link in site.data.navigation.main %}
  <a class="normal{% if link.right %} right{% endif %}" href="{{ link.url | relative_url }}">{{ link.title }}</a>
{% endfor %}

