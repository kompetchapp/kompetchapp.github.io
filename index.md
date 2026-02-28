---
layout: default
title: หน้าหลัก Kompetch App
---

# ยินดีต้อนรับสู่ Kompetch App! 👋
รวมบทความความรู้และเรื่องราวต่าง ๆ

### 🖥️ บทความสาย Tech ทั้งหมด
<ul>
  {% for post in site.categories.tech %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
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
