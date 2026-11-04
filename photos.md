---
layout: default
title: Photography
permalink: /photos/
---

<style>
.photo-page { width: min(1100px, 96vw); position: relative; left: 50%; transform: translateX(-50%); display: grid; grid-template-columns: minmax(260px, 38%) 1fr; gap: 3rem; align-items: start; margin: 2rem 0 3rem; }
.side { position: sticky; top: 1.5rem; background: var(--olive); aspect-ratio: 3 / 4; border-radius: 4px; overflow: hidden; }
.side img { width: 100%; height: 100%; object-fit: cover; display: block; }
.photo-text h1 { font-size: 2.6rem; margin: 0 0 1rem; }
.photo { margin: 0 0 3.5rem; }
.photo img { width: 100%; height: auto; display: block; border-radius: 4px; }
.photo .meta { font-size: .8rem; text-transform: uppercase; letter-spacing: .08em; margin: .9rem 0 .3rem; }
.photo h2 { margin: 0 0 .6rem; font-size: 1.5rem; }
@media (max-width: 800px) { .photo-page { grid-template-columns: 1fr; gap: 1.5rem; } .side { position: static; max-height: 70vh; } }
</style>

<div class="photo-page">
<div class="side">
<img src="{{ '/assets/photos-side.jpg' | relative_url }}" alt="" onerror="this.style.display='none'">
</div>
<div class="photo-text">
<h1>Photography</h1>
<p>Photography is another way I notice places and people. I am currently exploring film photography. Each photo comes with a short reflection.</p>

<div class="photo">
<img src="{{ '/assets/photo-1.jpg' | relative_url }}" alt="Describe what is in the photo" onerror="this.parentElement.style.display='none'">
<p class="meta">Place, Month Year</p>
<h2>Title of the first photo</h2>
<p>Write your reflection here. What did you see, and what did it make you think about?</p>
</div>

</div>
</div>
