---
layout: default
title: Home
---

<style>
.hero { margin: 2.5rem 0; }
.hero h1 { font-family: "Special Elite", "Courier New", Courier, monospace; font-weight: 400; font-size: 2.6rem; margin: 0 0 .2rem; letter-spacing: 0; }
.hero .role { color: #898274; margin: 0 0 1.2rem; }
.hero p { margin: 0 0 1rem; max-width: 620px; }
</style>
<div class="hero">
<h1>Thu Trang HA - Paige</h1>
<p class="role">MSc student in Local Development, University of Padua</p>
<p>I study how places develop and who gets to decide what development means. My interests are inequality, migration, education, and the relationship between people and places.</p>
</div>

<h2>Latest posts</h2>
<ul class="post-list">
{% for post in site.posts %}
<li>
<span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
<h3><a class="post-link" href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
</li>
{% endfor %}
</ul>
