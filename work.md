---
layout: page
title:  "Work"
---

<div class="work-thumbnails">
	{% for work in site.data.work %}
		<a href="{{ work.url }}" title="{{ work.title }}"><img src="{{ work.thumbnail }}" alt="{{ work.title }}"></a>
	{% endfor %}
</div>


