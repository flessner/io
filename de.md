# Wissensbasis

Alle Einträge:
<ul>
    {% for de in site.de %}
        <li><a href="{{ de.url }}">{{ de.title }}</a></li>
    {% endfor %}
</ul>
