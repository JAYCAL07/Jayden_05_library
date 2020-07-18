---
layout: layout.html
---

# 圖書資料

<ul>
{%- for books in collections.books reversed -%}
  <li>
    <a href="{{books.url}}">
      {{ books.data.title }}
    </a>
  </li>
{%- endfor -%}
</ul>

