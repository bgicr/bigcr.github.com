---
layout: page
title: Paper
---
{% include JB/setup %}

####Main Publication
<ul id='tag_list'>
{% for tag in site.tags %}
	<li class='tag_item' id='{{ tag[0]  }}'>
		<span class='tag_name'>{{ tag[0]  }}</span>
		<span>
			<ul>
				{% for post in tag[1] %}
				<li class='tag_post'><a href="{{ BASE_PATH }}{{ post.url  }}" title="{{ post.title  }}">{{ post.title  }}</a></li>
				{% endfor %}
			</ul>
		</span>
	</li>
{% endfor %}
</ul>
