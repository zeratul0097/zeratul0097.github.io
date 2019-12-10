---
layout: post
title: Linh Kiếm Sơn
permalink: /books/linh-kiem-son/
---
<style>
    p {
        margin-bottom: 5px
    }
</style>
# Danh sách chương
{% assign book = site.books | where:"book_name","linh-kiem-son" | sort: "chapter" %}
{% for chapter in book %}
<a href="{{ chapter.url }}">
    {{ chapter.title }}
</a>
{% endfor %}