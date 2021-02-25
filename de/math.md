# Mathematik

Alle Mathe Resourcen:
<ul>
    {% assign querry_url = page.url | remove: ".html" | append: "/" %}
    {% for ref in site.pages %}
        {% if ref.url contains querry_url %}
            <li><a href="{{ ref.url | absolute_url }}">{{ ref.title }}</a></li>
        {% endif %}
        <p>{{ querry_url }}</p>
        <p>{{ ref.url }}</p>
    {% endfor %}
</ul>
