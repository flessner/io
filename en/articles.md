# Articles

> 📓 Here are all the articles I have Notes on!

## All Articles
<!-- Modified from subdirs.html -->
{% assign querry_url = page.url | remove: ".html" | append: "/" %}
{% assign querry_test = querry_url | split: "/" %}
{% assign querry_test = querry_test.size | plus: 1 %}
{% for ref in site.pages %}
    {% if ref.url contains querry_url %}
        {% assign ref_test = ref.url | split: "/" %}
        {% assign ref_test = ref_test.size %}
        {% if querry_test == ref_test %}
            <li><a href="{{ ref.url | absolute_url | remove: '.html' }}">{{ ref.title }}</a> - {{ ref.author }}</li>
        {% endif %}
    {% endif %}
{% endfor %}

