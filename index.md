---
layout: main
title: 每日英文
---

歡迎來到每日英文練習！  
請從左側選擇日期來閱讀文章。
<p>目前有 {{ site.posts | size }} 篇文章</p>

# 全部文章偵測結果

<ul>
{% for post in site.posts %}
  <li>{{ post.date | date: "%Y-%m-%d" }} - {{ post.title }}</li>
{% else %}
  <li>目前沒有找到任何文章</li>
{% endfor %}
</ul>
