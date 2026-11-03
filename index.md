---
layout: default
title: Home
---

<style>
.hero { margin: 2.5rem 0; }
.hero h1 { font-size: 2.6rem; margin: 0 0 .2rem; }
.hero .role { color: #898274; margin: 0 0 1.2rem; }
.hero p { margin: 0 0 1rem; max-width: 620px; }
.links { display: flex; flex-wrap: wrap; gap: .6rem; margin-top: 1.4rem; }
.links a { display: inline-block; padding: .45rem 1.1rem; border: 1.5px solid #344B38; border-radius: 999px; font-size: .9rem; font-weight: 500; text-decoration: none; }
.links a:hover { background: #344B38; color: #fff; }
</style>
<div class="hero">
<h1>Thu Trang HA - Paige</h1>
<p class="role">MSc student in Local Development, University of Padua</p>
<p>I study how places develop and who gets to decide what development means. My interests are inequality, migration, education, and the relationship between people and places.</p>
<div class="links">
<a href="{{ '/posts/' | relative_url }}">Posts</a>
<a href="{{ '/about/' | relative_url }}">About me</a>
<a href="{{ '/photos/' | relative_url }}">Photography</a>
<a href="mailto:thutrang.ha@studenti.unipd.it">Email</a>
</div>
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
