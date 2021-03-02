---
description: 👋 Welcome to Torben Flessner’s Website!
---

# Home
**👋 Welcome to Torben Flessner's Website!**

## Resources
- [[de]]
- [[en]]

## Blog Posts
<ul>
    {% for post in site.posts %}
        <li><a href="{{ post.url | absolute_url | remove: '.html' }}">{{ post.title }}</a> - {{ post.date | date_to_string }}</li>
    {% endfor %}
</ul>

## Tech
This Site is hosted on GitHub Pages and also available as a [Repository](https://github.com/flessner/site).
The content is all just some Markdown files with [Foam](https://foambubble.github.io/foam/).
As a style it uses a modified version of GitHub's [Primer](https://github.com/pages-themes/primer) Theme.
All the pages can be found [here](./all).

[//begin]: # "Autogenerated link references for markdown compatibility"
[de]: de.md "Wissensbasis"
[en]: en.md "Knowledge Base"
[//end]: # "Autogenerated link references"