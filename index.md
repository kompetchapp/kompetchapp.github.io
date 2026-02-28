---
layout: default
title: หน้าหลัก Kompetch App
---

# ยินดีต้อนรับสู่ Kompetch App! 👋
รวมบทความความรู้และเรื่องราวต่าง ๆ

### 🖥️ Tech Insights
<ul class="post-list">
  {% for post in site.categories.tech limit:5 %}
    <li>
      <strong><a href="{{ post.url }}">{{ post.title }}</a></strong>
      <p>{{ post.excerpt | strip_html | truncatewords: 20 }}</p>
    </li>
  {% endfor %}
</ul>

### 🎭 หมวดไลฟ์สไตล์ (Life)
<ul>
  {% for post in site.categories.life %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
  
---
*สร้างโดย Kompetch*
