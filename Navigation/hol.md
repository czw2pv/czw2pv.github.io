---
layout: archive
permalink: /hol/
title: "Labs"
---

<div class="tiles">
  {% assign sorted_pages = site.pages | sort:"date" | reverse %}
	{% for page in sorted_pages %}
		{% if page.categories == "hol" %}
			{% include page-grid.html %}
		{% endif %} 
	{% endfor %}
</div>