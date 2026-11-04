---
layout: default
title: Posts
permalink: /posts/
---

<style>
body {
  overflow-x: hidden;
}

.site-header {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  z-index: 30;
  background: transparent;
}

.page-content {
  padding-top: 0;
}

.cover {
  position: relative;
  width: 100vw;
  margin-left: calc(50% - 50vw);
  height: 400px;
  background: var(--olive);
  overflow: hidden;
  margin-bottom: 2.5rem;
}

.cover img {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: center 77%;
  display: block;
}

.cover::after {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: rgba(47,48,32,.45);
}

.cover-inner {
  position: relative;
  z-index: 2;
  width: min(1100px, 96vw);
  height: 100%;
  margin: 0 auto;
  display: flex;
  align-items: flex-end;
  padding-bottom: 2rem;
}

.cover h1 {
  color: var(--light);
  font-size: 3rem;
  margin: 0;
}

.intro-text {
  max-width: 850px;
  font-size: 0.85rem;
  line-height: 1.65;
  color: #777;
  margin-bottom: 1.8rem;
}

.intro-text p {
  margin-bottom: 0.8rem;
}

@media (max-width: 600px) {
  .cover {
    height: 300px;
  }

  .cover h1 {
    font-size: 2.2rem;
  }

  .intro-text {
    font-size: 0.82rem;
    line-height: 1.65;
  }
}
</style>

<div class="cover">
  <img src="{{ '/assets/posts-coverr.jpg' | relative_url }}" alt="" onerror="this.style.display='none'">
  <div class="cover-inner">
    <h1>Posts</h1>
  </div>
</div>

<div class="intro-text">
  <p>
    This is where I collect notes and reflections from my studies, readings, and conversations, as well as questions that keep me thinking beyond the classroom. My writing mainly explores ideas and debates around development, including power, inequality, migration, climate change, education, and the relationships between people and places. I write in English to share my thoughts with colleagues and a wider international audience, and in Vietnamese to connect with readers back home and express certain ideas in my own language.
  </p>

  <p>
    Đây là nơi tôi ghi lại những ghi chú và suy ngẫm từ việc học, những gì tôi đọc và các cuộc trò chuyện, cùng những câu hỏi vẫn tiếp tục khiến tôi suy nghĩ sau giờ học. Nội dung chủ yếu xoay quanh các ý tưởng và tranh luận về phát triển, bao gồm quyền lực, bất bình đẳng, di cư, biến đổi khí hậu, giáo dục và mối quan hệ giữa con người với nơi chốn. Tôi viết bằng tiếng Anh để chia sẻ suy nghĩ với bạn bè, đồng nghiệp và độc giả quốc tế, và bằng tiếng Việt để kết nối với độc giả ở "nhà", cũng như diễn đạt một số suy nghĩ bằng ngôn ngữ của chính mình.
  </p>
</div>

<ul class="post-list">
  {% for post in site.posts %}
  <li>
    <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
    <h3>
      <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </h3>
  </li>
  {% endfor %}
</ul>
