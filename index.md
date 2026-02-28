---
layout: default
title: หน้าหลัก Kompetch App
---

# ยินดีต้อนรับสู่ Kompetch App! 👋
พื้นที่แบ่งปันความรู้ ประสบการณ์ และเรื่องราวที่น่าสนใจรอบตัว

---

### 🚀 สาระและความรู้ (Insight & Knowledge)
*รวมบทความเจาะลึก เทคโนโลยี และเทคนิคการทำงาน*
<ul class="post-list">
  {% for post in site.categories.insight limit:5 %}
    <li>
      <strong><a href="{{ post.url }}">{{ post.title }}</a></strong>
      <p>{{ post.excerpt | strip_html | truncatewords: 15 }}</p>
    </li>
  {% endfor %}
</ul>

### ✍️ ถอดบทความ & ความคิด (Reflections)
*ไดอารี่ทางความคิด มุมมองต่อสังคม และการพัฒนาตนเอง*
<ul class="post-list">
  {% for post in site.categories.thought limit:5 %}
    <li>
      <strong><a href="{{ post.url }}">{{ post.title }}</a></strong>
      <p>{{ post.excerpt | strip_html | truncatewords: 15 }}</p>
    </li>
  {% endfor %}
</ul>

### 🎁 รีวิวป้ายยา (Reviews)
*แกะกล่อง Gadget, แนะนำหนังสือ, หนังดี หรือร้านอาหารที่ชอบ*
<ul class="post-list">
  {% for post in site.categories.review limit:5 %}
    <li>
      <strong><a href="{{ post.url }}">{{ post.title }}</a></strong>
      <p>{{ post.excerpt | strip_html | truncatewords: 15 }}</p>
    </li>
  {% endfor %}
</ul>

### 🌍 ไลฟ์สไตล์ & ทั่วไป (Lifestyle)
*เรื่องราวเบ็ดเตล็ด การเดินทาง และกิจกรรมยามว่าง*
<ul class="post-list">
  {% for post in site.categories.lifestyle limit:5 %}
    <li>
      <strong><a href="{{ post.url }}">{{ post.title }}</a></strong>
      <p>{{ post.excerpt | strip_html | truncatewords: 15 }}</p>
    </li>
  {% endfor %}
</ul>

---
*สร้างอย่างตั้งใจโดย Kompetch*
