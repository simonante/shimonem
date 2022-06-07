---
layout: books
title: Reading List
permalink: /reading/
---

<script>
    var quotes = [
        '{% include quotes-eccl-i.html %}',
        '{% include quotes-solovyev-i.html %}'
    ];

    function random-quote-i() {
        var i = parseInt(Math.random() * quotes.length);
        location.href = quotes[i];
    }
</script>

<a href="#" onclick="random-quote-i();">Random</a>

===

<script>
    var quotes = [
        '{% include quotes-eccl-i.html %}',
        '{% include quotes-solovyev-i.html %}'
    ];

    function random-quote-i() {
        var i = parseInt(Math.random() * quotes.length);
        location.href = quotes[i];
        document.getElementById('quote-i').innerHTML;
    }
</script>
       
<p id="quote-i"></p>
