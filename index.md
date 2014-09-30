---
layout: page
title: Andrew Learns Jekyll
tagline: And Strengthens his VIM skills 
---
{% include JB/setup %}

## I use vim
I am sure you we all have our favorite text-editors, but here is the man page for a wonderful commandline text editor called [vimtutor](http://linuxcommand.org/man_pages/vimtutor1.html).  Vimtutor has drastically increased my editing speeds.

## Installing vim
As root.

	'$ apt-get install vim'

## Starting vimtutor

	'$ vimtutor' 

And follow the tutorial.

Depending on the time you spend with experimentation, this tutorial should take between 25-35 minutes.


## I use [Jekyll](http://jekyllrb.com) for generating this site.

================================================================================
    
### Posts

This blog will eventually facilitate some of my projects, intrests, and life.

Here's my "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

- Skills
- Book list
- Projects
- Sailboat
- 3D Printer
- Wilderness
- 

