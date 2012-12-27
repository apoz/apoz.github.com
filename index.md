---
layout: page
title: Well Thought
tagline: Supporting tagline
---
{% include JB/setup %}

<article>
  <time datetime="{{ site.posts.first.date | xmlschema }}">{{ site.posts.first.date | date: "%B %d, %Y" }}</time>
  <h2><a href="{{ site.posts.first.url }}">{{ site.posts.first.title }}</a></h2>
  {{ site.posts.first.content }}
</article>
  
<div class="comments">
 {% include JB/comments %}
</div> 

<h2> Older Posts </h2>
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>