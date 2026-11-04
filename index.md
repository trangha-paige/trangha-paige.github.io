---
layout: default
title: Home
---

<style>
.hero { width: min(1100px, 96vw); position: relative; left: 50%; transform: translateX(-50%); display: grid; grid-template-columns: 1.15fr 1fr; gap: 3rem; align-items: center; margin: 2rem 0 3rem; }
.hero-photo { background: var(--olive); min-height: 560px; border-radius: 4px; overflow: hidden; }
.hero-photo img { width: 100%; height: 560px; object-fit: cover; object-position: center 30%; display: block; }
.hero-text h1 { font-family: "Special Elite", "Courier New", Courier, monospace; font-weight: 400; font-size: 2.4rem; line-height: 1.2; letter-spacing: 0; margin: 0 0 .6rem; }
.hero-text .role { font-weight: 700; text-transform: uppercase; letter-spacing: .08em; font-size: .85rem; margin: 0 0 1.2rem; }
.hero-text p { margin: 0 0 1rem; }
.links { display: flex; flex-wrap: wrap; gap: .6rem; margin-top: 1.4rem; }
.page-content .links a, .page-content .links a:visited { display: inline-block; padding: .5rem 1.3rem; background: var(--dark); color: var(--light); border-radius: 999px; font-size: .95rem; font-weight: 700; text-decoration: none; }
.page-content .links a:hover { background: var(--orange); color: var(--dark); }
@media (max-width: 800px) { .hero { grid-template-columns: 1fr; gap: 1.5rem; } .hero-photo, .hero-photo img { min-height: 340px; height: 340px; } }
</style>
<div class="hero">
<div class="hero-photo">
<img src="{{ '/assets/profilee.jpg' | relative_url }}" alt="Thu Trang HA" onerror="this.style.display='none'">
</div>
<div class="hero-text">
<h1>Thu Trang HA - Paige</h1>
<p class="role">MA Student in Local Development, University of Padua</p>
<p>I study how places develop, who shapes development, and what alternatives we can imagine. My interests include power, inequality, migration, climate change, education, and the relationships between people and places. Coming from Vietnam and studying in Europe, I often find myself questioning the ideas of development I encounter here through the experiences and realities I know from home.</p>
<p>This blog is where I write about ideas from my studies, reflect on what I read and learn, and explore questions that stay with me beyond the classroom.</p>
<p>I'm also interested in critical cartography and how maps shape the way we see the world. Outside my studies, I enjoy photography and am currently exploring film photography.</p>
<p>You can find my <a href="https://your-cartography-portfolio-url/">critical cartography projects</a> and <a href="{{ '/photos/' | relative_url }}">photography</a>, or learn more <a href="{{ '/about/' | relative_url }}">about me</a>.</p>
<div class="links">
<a href="mailto:hatrangatwork89@gmail.com">Email</a>
<a href="https://www.linkedin.com/in/trang-ha-paige/">LinkedIn</a>
</div>
</div>
</div>
