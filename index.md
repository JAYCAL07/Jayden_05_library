---
layout: layout.html
---

# 圖書資料

- <a href="/books/HTML and CSS.md">HTML and CSS</a>
- <a href="/books/JavaScript and jQuery.md">JavaScript and jQuery</a>
- <a href="/books/Head First HTML and CSS.md">Head First HTML and CSS</a>
- <a href="/books/Digital Minimalism.md">Digital Minimalism</a>

<ul>
{%- for books in collections.books reversed -%}
  <li>
    <a href="{{books.url}}">
      {{ books.data.title }}
    </a>
  </li>
{%- endfor -%}
</ul>
