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

    function random-quote-i() {
        var i = parseInt(Math.random() * sites.length);
        location.href = sites[i];
    }
</script>

<a href="#" onclick="random-quote-i();">Random</a>
<ul>
  <p>
      randomSite();
  </p>
</ul>
