---
layout: article
permalink: /workshops/
title: Step by step Guides
date: 2018-03-27
categories: guide
tags: [step by step, guide, Azure Stack, MAS, How to, template]
comments: true
author: Fredrik_Nilsson
featured: True
image: fredriknilsson_
  feature: 
  teaser: fredriknilsson_.jpg
  thumb: 
excerpt: Step by step Guides to help ypu get started.
---
{% include toc.html %}
{% include toc.html %}

## Introduction

Stay Tuned... Coming Soon...

<div class="tiles">
	{% assign sorted_pages = site.pages | sort:"date" | reverse %}
	{% for page in sorted_pages %}
		{% if page.categories == "workshops" %}
			{% include page-grid.html %}
		{% endif %} 
	{% endfor %}
</div>
