---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: main
---

# 1 000 000 words in 1000 sets of 1000
Inspired by [Visakan Veerasamy](http://visakanv.com/1000/) I will use this page to write out my 1000 word vomits. The purpose of them is to gain as much experience with writing as possible. 

# Recent posts

<ul>
  {% for post in site.categories.1000 %}
    <li>
    <a href="{{ post.url }}">{{ post.title }}</a> <b>{{ post.date | date: "%d %B %Y" }}</b> 
    </li>
  {% endfor %}
</ul>

