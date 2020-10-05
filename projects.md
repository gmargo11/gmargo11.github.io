---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# layout: home
#---

layout: default
title: Home
---

<h1> About Me </h1>


<h1>Latest Posts</h1>

{% for post in site.posts %}
<h2> <a href="{{ post.url }}">{{ post.title }}</a></h2>
<p>{{ post.excerpt }}</p>
{% endfor %}
