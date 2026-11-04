---
layout: default
title: Posts
permalink: /posts/
---

<style>
body { overflow-x: hidden; }
.site-header { position: absolute; top: 0; left: 0; right: 0; z-index: 30; background: transparent; }
.page-content { padding-top: 0; }
.cover { position: relative; width: 100vw; margin-left: calc(50% - 50vw); height: 400px; background: var(--olive); overflow: hidden; margin-bottom: 2.5rem; }
.cover img { position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover; object-position: center 70%; display: block; }
.cover::after { content: ""; position: absolute; top: 0; left: 0; right: 0; bottom: 0; background: rgba(47,48,32,.45); }
.cover-inner { position: relative; z-index: 2; width: min(1100px, 96vw); height: 100%; margin: 0 auto; display: flex; align-items: flex-end; padding-bottom: 2rem; }
.cover h1 { color: var(--light); font-size: 3rem; margin: 0; }
@media (max-width: 600px) { .cover { height: 300px; } .cover h1 { font-size: 2.2rem; } }
</style>

<div class="cover">
<img src="{{ '/assets/posts-cover.jpg' | relative_url }}" alt="" onerror="this.style.display='none'">
<div class="cover-inner"><h1>Posts</h1></div>
</div>

This is where I collect notes and reflections from my studies, readings, and conversations, as well as questions that keep me thinking beyond the classroom. Some posts are brief thoughts, while others are attempts to explore an idea in more depth. I write in English to share my thoughts with colleagues and a wider international audience, and in Vietnamese to connect with readers back home and express certain ideas in my own language. Some posts are in both languages.

<ul class="post-list">
  {% for post in site.posts %}
  <li>
    <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
    <h3><a class="post-link" href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
  </li>
  {% endfor %}
</ul>
