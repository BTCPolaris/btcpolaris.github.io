---
title: 北极星BTC
---

# 北极星 BTC · BTCPolaris

这里是我的长期主义实验室，也是比特币定投与学习笔记的基站。

- 2017 年进入币圈，经历完整牛熊
- 专注：BTC 定投实践、注意力训练、英语与自我修炼
- 原则：长期主义、少做决定、少动手，多持有

这是第一版首页，后面会慢慢补充板块和文章目录。

---

## 最近文章

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">
        {{ post.date | date: "%Y-%m-%d" }} · {{ post.title }}
      </a>
    </li>
  {% endfor %}
</ul>
