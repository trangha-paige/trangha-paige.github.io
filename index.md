---
layout: default
title: Home
---

<style>
.hero { width: min(1100px, 96vw); position: relative; left: 50%; transform: translateX(-50%); display: grid; grid-template-columns: 1.15fr 1fr; gap: 3rem; align-items: center; margin: 2rem 0 3rem; }
.hero-photo { background: var(--olive); min-height: 560px; border-radius: 4px; overflow: hidden; }
.hero-photo img { width: 100%; height: 560px; object-fit: cover; object-position: center 20%; display: block; }
.hero-text .role { font-weight: 700; text-transform: uppercase; letter-spacing: .08em; font-size: .85rem; margin: 0 0 1.2rem; }
.hero-text p { margin: 0 0 1rem; }
.links { display: flex; flex-wrap: wrap; gap: .6rem; margin-top: 1.4rem; }
.page-content .links a, .page-content .links a:visited { display: inline-block; padding: .5rem 1.3rem; background: var(--dark); color: var(--light); border-radius: 999px; font-size: .95rem; font-weight: 700; text-decoration: none; }
.page-content .links a:hover { background: var(--orange); color: var(--dark); }
@media (max-width: 800px) { .hero { grid-template-columns: 1fr; gap: 1.5rem; } .hero-photo, .hero-photo img { min-height: 340px; height: 340px; } }
</style>
<div class="hero">
<div class="hero-photo">
<img src="{{ '/assets/profile.jpg' | relative_url }}" alt="Thu Trang HA" onerror="this.style.display='none'">
</div>
<div class="hero-text">
<p class="role">MA student in Local Development, University of Padua</p>
<p>I study how places develop, who shapes development, and what alternatives we can imagine. My interests include power, inequality, migration, climate change, education, and the relationships between people and places. Coming from Vietnam and studying in Europe, I often find myself questioning the ideas of development I encounter here through the experiences and realities I know from home.</p>
<p>This blog is where I write about ideas from my studies, reflect on what I read and learn, and explore questions that stay with me beyond the classroom.</p>
<p>I'm also interested in critical cartography and how maps shape
