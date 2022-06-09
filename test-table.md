---
layout: page
title: test table
permalink: /test-table/
---

|---|---|
{% for books in site.books -%}
{% if books.title -%}
|[{{ books.title }}]({{ books.url }})  |   — {{ books.author }}  |
{% endif %}
{%- endfor -%}
          
