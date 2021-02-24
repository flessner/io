# Blog

Here are some articles:
    {% for post in site.posts %}
            - <a href="{{ post.url | absolute_url }}">{{ post.title }}</a> - {{ post.date | date_to_string }} - {{ post.tags }}
    {% endfor %}

And some text...

