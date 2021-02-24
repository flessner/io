# Home

**👋 Welcome to this new Website!**

Here are some articles:
<ul>
    {% for post in site.posts %}
        <li>
            <a href="{{ post.url | absolute_url }}">{{ post.title }}</a> - {{ post.date | date_to_string }}
        </li>
    {% endfor %}
</ul>
