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
        document.getElementById('quote-i').innerHTML
    }
</script>
       
<p id="quote-i"></p>

===

<script>
    function random_item(items)
    {

    return items[Math.floor(Math.random()*items.length)];

    }

    var items = ["{% include quotes-eccl-i.html %}", "{% include quotes-solovyev-i.html %}"];
    console.log(random_item(items));
</script>
