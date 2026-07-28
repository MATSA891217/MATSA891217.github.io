---
layout: default
title: 首页
---

{% for post in site.posts %}
<div class="post-card">
  <div class="post-preview">
    <h2><a href=" ">{{ post.title }}</a ></h2>
    <p class="post-meta">{{ post.date | date: "%Y年%m月%d日" }}</p >
    <div class="post-content">
      {{ post.content }}
    </div>
  </div>
</div>
{% endfor %}
