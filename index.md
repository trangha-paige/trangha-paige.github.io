---
layout: default
title: Home
---

<style>
.hero { width: min(1100px, 96vw); position: relative; left: 50%; transform: translateX(-50%); display: grid; grid-template-columns: 1.15fr 1fr; gap: 3rem; align-items: center; margin: 2rem 0 3rem; }
.hero-photo { background: #DED7C9; min-height: 560px; border-radius: 4px; overflow: hidden; }
.hero-photo img { width: 100%; height: 560px; object-fit: cover; display: block; }
.hero-text .role { color: #898274; margin: 0 0 1.2rem; }
.hero-text p { margin: 0 0 1rem; }
.links { display: flex; flex-wrap: wrap; gap: .6rem; margin-top: 1.4rem; }
.links a { display: inline-block; padding: .45rem 1.1rem; border: 1.5px solid #344B38; border-radius: 999px; font-size: .9rem; font-weight: 500; text-decoration: none; }
.links a:hover { background: #344B38; color: #fff; }
@media (max-width: 800px) { .hero { grid-template-columns: 1fr; gap: 1.5rem; } .hero-photo, .hero-photo img { min-height: 340px; height: 340px; } }
</style>
<div class="hero">
<div class="hero-photo">
<img src="{{ '/assets/profile.jpg' | relative_url }}" alt="Thu Trang HA" onerror="this.style.display='none'">
</div>
<div class="hero-text">
<p class="role">MSc student in Local Development, University of Padua</p>
<p>I study how places develop and who gets to decide what development means. My interests are inequality, migration, education, and the relationship between people and places.</p>
<p>I am also interested in critical cartography. You can see my work in my <a href="https://YOUR-CARTOGRAPHY-PORTFOLIO-URL">critical cartography portfolio</a>, and read more about my studies and background under <a href="{{ '/research/' | relative_url }}">Research</a>.</p>
<div class="links">
<a href="mailto:hatrangatwork89@gmail.com">Gmail</a>
<a href="https://www.linkedin.com/in/YOUR-NAME">LinkedIn</a>
</div>
</div>
</div>
