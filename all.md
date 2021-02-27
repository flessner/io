# All the pages 🤯

<ul>
{% for ref in site.pages %}
    {% if ref.url contains '.xml' or ref.url contains 'assets' %}{% else %}
        <li>[<a href="{{ ref.url | absolute_url | remove: '.html' }}">{{ ref.title }}</a>]</li>
    {% endif %}
{% endfor %}
</ul>
