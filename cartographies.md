---
layout: default
title: "C/artographies"
permalink: /cartographies/
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
.page-content p img { max-width: 100%; height: auto; display: block; }
@media (max-width: 600px) { .cover { height: 300px; } .cover h1 { font-size: 2.2rem; } }
</style>

<div class="cover">
<img src="{{ '/assets/cartographies-cover.jpg' | relative_url }}" alt="" onerror="this.style.display='none'">
<div class="cover-inner"><h1>C/artographies</h1></div>
</div>

My critical cartography work. Each map comes with a reading of what its parts mean.

## Title of the first map

![Describe the map]({{ '/assets/carto-1.jpg' | relative_url }})

Write one short paragraph about what this map is and why you made it.

**Reading the map**

1. **First part.** What it shows and what it means.
2. **Second part.** What it shows and what it means.
3. **Third part.** What it shows and what it means.

## Title of the second map

![Describe the map]({{ '/assets/carto-2.jpg' | relative_url }})

Write one short paragraph here.

**Reading the map**

1. **First part.** What it shows and what it means.
2. **Second part.** What it shows and what it means.
