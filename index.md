---
layout: page
title: Flex on the World.
tagline: A work in progress...
---
{% include JB/setup %}

##The author and Maxwell.

![Alt text](/assets/andrew_max_intruck.jpg "Author and Dog")

## I use [Jekyll](http://jekyllrb.com) for generating this site.

    
## Posts

This blog will eventually facilitate some of my projects, intrests, and life.

Here's my "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

### To-Do

- Skills
- Book list
- Projects
- Sailboat
- 3D Printer
- Wilderness
- 

