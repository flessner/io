# Blog

Here are some articles:
<ul>
    {% for post in site.posts %}
        <li>
            <a href="{{ post.url }}">{{ post.title }}</a>
            {{ post.excerpt }}
        </li>
    {% endfor %}
</ul>

And some text...

