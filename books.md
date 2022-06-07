---
layout: books
title: Reading List
permalink: /reading/
---

<script>
    var sites = [
        '{% include quote-i.html %}',
        '{% include quote-ii.html %}'
    ];

    function randomSite() {
        var i = parseInt(Math.random() * sites.length);
        location.href = sites[i];
    }
</script>
<a href="#" onclick="randomSite();">Random</a>
