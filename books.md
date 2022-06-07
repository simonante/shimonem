---
layout: books
title: Reading List
permalink: /reading/
---

<script>
    var quotes = [
        '{% include quote-i.html %}',
        '{% include quote-ii.html %}'
    ];

    function random-quote-i() {
        var i = parseInt(Math.random() * quotes.length);
        location.href = quotes[i];
    }
</script>

<a href="#" onclick="random-quote-i();">Random</a>
