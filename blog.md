# Blog

Here are some articles:
<ul>
    {% for post in site.posts %}
        <li>
            <a href="{{ post.url | absolute_url }}">{{ post.title }} - {{ post.date | date_to_string }}</a>
            {{post.tags}}
        </li>
    {% endfor %}
</ul>

And some text...

