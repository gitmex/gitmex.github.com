---
layout: page
title: gitmex!
tagline: Where brownian motion goes to die
---
{% include JB/setup %}
<ul class="posts">
  {% for post in site.posts %}
  	<div class="postContainer">
		<div class="postHeader">
			<li>
				 
				<a class="postTitle" href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
			
				 &laquo;
			
				<span class="postDate">{{ post.date | date_to_string }}</span>
			
			
			</li>
				
				
		</div>

		<div class="postText">
	    	{{ post.content }}
		</div>
	</div>
  {% endfor %}
</ul>