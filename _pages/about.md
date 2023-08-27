---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<nav>
    <ul>
        <li><a href="#about-us" style="color:white;">简介</a></li>
        <li><a href="#people" style="color:white;">成员</a></li>
        <li><a href="#publications" style="color:white;">论文</a></li>
        <li><a href="#talks" style="color:white;">报告</a></li>
        <li><a href="#alumni" style="color:white;">毕业生</a></li>
    </ul>
</nav>

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
