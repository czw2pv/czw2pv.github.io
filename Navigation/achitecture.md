---
layout: archive
permalink: /achitecture/
title: "Achitecture"
---

<div class="tiles">
	{% assign sorted_pages = site.pages | sort:"date" | reverse %}
	{% for page in sorted_pages %}
		{% if page.categories == "achitecture" %}
			{% include page-grid.html %}
		{% endif %} 
	{% endfor %}
</div>
