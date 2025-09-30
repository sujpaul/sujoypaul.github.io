---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: "AI Blog: Exploring business value through technology and strategy "
---

# Welcome to My AI Blog

This is a personal blog about AI, ML, and Deep Learning.  

Check out my latest posts below:

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}