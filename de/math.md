# Mathematik

Alle Mathe Resourcen:
<ul>
    {% for ref in site.pages %}
        {% if site.url contains ref.url %}
            <li><a href="{{ ref.url | absolute_url }}">{{ ref.title }}</a></li>
        {% endif %}
        <p>{{ page.url }}</p>
        <p>{{ ref.url }}</p>
    {% endfor %}
</ul>
