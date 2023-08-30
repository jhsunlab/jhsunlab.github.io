---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<head>
	<style>
		button {
			background-color: white;
  			border: 2px solid #3F50B6;
  			color: #3F50B6;
  			padding: 2px 6px;
  			text-align: center;
  			text-decoration: none;
  			display: inline-block;
  			font-size: 14px;
  			margin-bottom: 0;
  			cursor: pointer;
			border-radius: 6px;
		}
		button:hover {
			background-color: #3F50B6;
			color: white;
		}
	</style>
</head>

<span class='anchor' id='about-us'></span>
{% include_relative includes/about-us.md %}

<span class='anchor' id='people'></span>
{% include_relative includes/people.md %}

<span class='anchor' id='publications'></span>
{% include_relative includes/publications.md %}

<span class='anchor' id='talks'></span>
{% include_relative includes/talks.md %}

<span class='anchor' id='alumni'></span>
{% include_relative includes/alumni.md %}
