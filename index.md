---
layout: page
title: Indexing!
tagline: Where brownian motion goes to die
---
{% include JB/setup %}
<ul class="posts">
  {% for post in site.posts %}
  	<div class="postContainer">
		<div class="postHeader">
			<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
		</div>

		<div class="postContent">
	    	{{ post.content }}
		</div>
	</div>
  {% endfor %}
</ul>