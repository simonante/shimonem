---
layout: page
title: Reading List
permalink: /reading-old/
---
<!--
<tr>
<td markdown="span"><a href="URL" target="_blank">TITLE</a></td>
<td markdown="span"> &nbsp;— AUTHOR</td>
</tr>
-->

## Read

|---|---|
{% for books in site.books -%}
{% if books.title -%}
|[{{ books.title }}]({{ books.url }})  |   — {{ books.author }}  |
{% endif %}
{%- endfor -%}
          
          
  <details>
  <summary>Good books:</summary>

<table>
<colgroup>
<col width="60%" />
<col width="50%" />
</colgroup>
<tbody>
<tr>
<td markdown="span"><a href="https://www.simonante.com/reading/shelton-h-s_the-science-and-fine-art-of-fasting">The Science & Fine Art of Fasting</a></td>
<td markdown="span"> &nbsp;— Herbert M. Shelton</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/369010.A_Study_of_History" target="_blank">A Study of History - vol. I-XII</a></td>
<td markdown="span"> &nbsp;— Arnold J. Toynbee</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/904538.The_Book_of_Tea" target="_blank">The Book of Tea</a></td>
<td markdown="span"> &nbsp;— Kakuzō Okakura</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/2000176.Hyperion_oder_Der_Eremit_in_Griechenland" target="_blank">Hyperion; or, The Hermit in Greece</a></td>
<td markdown="span"> &nbsp;— Friedrich Hölderlin</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1923820.The_Holy_Bible" target="_blank">Bible: King James Version</a></td>
<td markdown="span"> &nbsp;—</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/821535.The_Torah" target="_blank">The Torah: The Five Books of Moses</a></td>
<td markdown="span"> &nbsp;—</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/2158305.The_Arden_Dictionary_of_Shakespeare_Quotations" target="_blank">The Arden Dictionary of Shakespeare Quotations</a></td>
<td markdown="span"> &nbsp;— Jane Armstrong</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1692216.Origins" target="_blank">Origins: A Short Etymological Dictionary of Modern English</a></td>
<td markdown="span"> &nbsp;— Eric Partridge</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/18490595-zibaldone" target="_blank">Zibaldone</a></td>
<td markdown="span"> &nbsp;— Giacomo Leopardi</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/87665.Orthodoxy?" target="_blank">Orthodoxy</a></td>
<td markdown="span"> &nbsp;— G.K.Chesterton</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/40137863-parerga-et-paralipomena?" target="_blank">Parerga et Paralipomena</a></td>
<td markdown="span"> &nbsp;— Arthur Schopenhauer</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/19436223-lonely-planet-south-america?from_search=true&from_srp=true&qid=U5N0oXjkLe&rank=2" target="_blank">Lonely Planet South America</a></td>
<td markdown="span"> &nbsp;— Lonely Planet</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/5787.The_Aleph_and_Other_Stories" target="_blank">The Aleph</a></td>
<td markdown="span"> &nbsp;— Jorge Luis Borges</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/426504.Ficciones" target="_blank">Ficciones</a></td>
<td markdown="span"> &nbsp;— Jorge Luis Borges</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/204523.Wholeness_and_the_Implicate_Order" target="_blank">Wholeness and the Implicate Order</a></td>
<td markdown="span"> &nbsp;— David Bohm</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/573609.The_Notebooks_of_Joseph_Joubert" target="_blank">The Notebooks of Joseph Joubert</a></td>
<td markdown="span"> &nbsp;— Joseph Joubert</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/223403.Deschooling_Society" target="_blank">Deschooling Society</a></td>
<td markdown="span"> &nbsp;— Ivan Illich</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/449407.Pens_es" target="_blank">Pensées</a></td>
<td markdown="span"> &nbsp;— Blaise Pascal</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/26059079-jerusalem-and-athens" target="_blank">Jerusalem and Athens</a></td>
<td markdown="span"> &nbsp;— Leo Strauss</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1879755.Nicholas_of_Cusa_on_Learned_Ignorance" target="_blank">On Learned Ignorance</a></td>
<td markdown="span"> &nbsp;— Nicolas of Cusa</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/110795.Catechism_of_the_Catholic_Church" target="_blank">Catechism of the Catholic Church</a></td>
<td markdown="span"> &nbsp;— The Catholic Church</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/50480.Complete_Poems" target="_blank">Complete Poems</a></td>
<td markdown="span"> &nbsp;— Charles Baudelaire</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/46048924-schindler" target="_blank">Schindler</a></td>
<td markdown="span"> &nbsp;— James Steele</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/14577484-tadao-ando" target="_blank">Conversations with Students</a></td>
<td markdown="span"> &nbsp;— Tadao Andō</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/30528.Observations_on_the_Feeling_of_the_Beautiful_and_Sublime" target="_blank">Observations on the Feeling of the Beautiful and Sublime</a></td>
<td markdown="span"> &nbsp;— Immanuel Kant</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/18288.Critique_of_Pure_Reason" target="_blank">Critique of Pure Reason</a></td>
<td markdown="span"> &nbsp;— Immanuel Kant</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/46002.Critique_of_Cynical_Reason" target="_blank">Critique of Cynical Reason</a></td>
<td markdown="span"> &nbsp;— Peter Sloterdijk</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/35218850-intelligence-and-spirit" target="_blank">Intelligence and Spirit</a></td>
<td markdown="span"> &nbsp;— Reza Negarestani</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/883405.Bartlett_s_Familiar_Quotations" target="_blank">The Ever-Present Origin</a></td>
<td markdown="span"> &nbsp;— Jean Gebser</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/162888.Selected_Poetry_and_Prose" target="_blank">Selected Poetry and Prose</a></td>
<td markdown="span"> &nbsp;— Alexander Pope</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/767958.Leisure" target="_blank">Leisure: The Basis of Culture</a></td>
<td markdown="span"> &nbsp;— Josef Pieper</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/67896.Tao_Te_Ching" target="_blank">Tao Te Ching</a></td>
<td markdown="span"> &nbsp;— Lao Tzu</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/381217.Ressentiment?" target="_blank">Ressentiment</a></td>
<td markdown="span"> &nbsp;— Max Scheler</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/11084555-saint-francis-of-assisi" target="_blank">Saint Francis of Assisi</a></td>
<td markdown="span"> &nbsp;— G.K.Chesterton</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/4037713-patterns-in-nature?" target="_blank">Patterns In Nature</a></td>
<td markdown="span"> &nbsp;— Peter S. Stevens</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/41750170-an-immanent-metaphysics" target="_blank">An Immanent Metaphysics</a></td>
<td markdown="span"> &nbsp;— Forrest Landry</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/337520.Deceit_Desire_and_the_Novel" target="_blank">Deceit, Desire and the Novel</a></td>
<td markdown="span"> &nbsp;— René Girard</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/400379.Before_the_Deluge" target="_blank">Before the Deluge: A Portrait of Berlin in the 1920s</a></td>
<td markdown="span"> &nbsp;— Otto Friedrich</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/10107076-the-politics-of-experience-and-the-bird-of-paradise?" target="_blank">The Politics of Experience</a></td>
<td markdown="span"> &nbsp;— R.D.Laing</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/17335264-awaiting-god" target="_blank">Awaiting God</a></td>
<td markdown="span"> &nbsp;— Simone Weil</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/14704.Faust" target="_blank">Faust: Part I and II</a></td>
<td markdown="span"> &nbsp;— J.W.Goethe</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/801754.The_Decline_of_the_West" target="_blank">The Decline of the West</a></td>
<td markdown="span"> &nbsp;— Oswald Spengler</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/144870.The_Conference_of_the_Birds" target="_blank">The Conference of the Birds</a></td>
<td markdown="span"> &nbsp;— Attar of Nishapur</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/761925.The_Guide_for_the_Perplexed?" target="_blank">The Guide for the Perplexed</a></td>
<td markdown="span"> &nbsp;— M. Maiomonides</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/25314120-on-exactitude-in-science" target="_blank">On Exactitude in Science</a></td>
<td markdown="span"> &nbsp;— Jorge Luis Borges</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/184565.What_s_Wrong_with_the_World?" target="_blank">The Cambr. His. of Nineteenth-Century Polit. Thought</a></td>
<td markdown="span"> &nbsp;— G.S.Jones</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/184565.What_s_Wrong_with_the_World" target="_blank">What's Wrong with the World</a></td>
<td markdown="span"> &nbsp;— G.K.Chesterton</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/81912.Human_Action" target="_blank">Human Action: A Treatise on Economics</a></td>
<td markdown="span"> &nbsp;— Ludwig von Mises</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/7669038-christianity-truth-and-weakening-faith" target="_blank">Christianity, Truth, and Weakening Faith</a></td>
<td markdown="span"> &nbsp;— Gianni Vattimo</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/39659832-100-whites" target="_blank">100 Whites</a></td>
<td markdown="span"> &nbsp;— Kenya Hara</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1760564.Amiel_s_Journal" target="_blank">Amiel's Journal</a></td>
<td markdown="span"> &nbsp;— Henri-Frédéric Amiel</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/18867922-the-confessions-of-st-augustine" target="_blank">The Confessions of St. Augustine</a></td>
<td markdown="span"> &nbsp;— Augustine of Hippo</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1752046.Virtuous_War" target="_blank">Virtuous War</a></td>
<td markdown="span"> &nbsp;— James Der Derian</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/581256.The_Life_Divine" target="_blank">The Life Divine</a></td>
<td markdown="span"> &nbsp;— Sri Aurobindo</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/386885.The_True_and_Only_Heaven" target="_blank">Progress and Its Critics</a></td>
<td markdown="span"> &nbsp;— Christopher Lasch</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/36448501-the-bitcoin-standard" target="_blank">The Bitcoin Standard</a></td>
<td markdown="span"> &nbsp;— Saifedean Ammous</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1039575.What_Computers_Can_t_Do" target="_blank">What Computers Can't Do: A Critique of Artificial Reason</a></td>
<td markdown="span"> &nbsp;— Hubert L. Dreyfus</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/16132796-the-use-of-knowledge-in-society" target="_blank">The Use of Knowledge in Society</a></td>
<td markdown="span"> &nbsp;— Friedrich Hayek</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/18579246-karl-l-with-s-view-of-history" target="_blank">Karl Löwith's View of History</a></td>
<td markdown="span"> &nbsp;— Berthold Riesterer</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/851541.Process_and_Reality" target="_blank">Process and Reality</a></td>
<td markdown="span"> &nbsp;— Alfred North Whitehead</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/2888219-process-relational-philosophy" target="_blank">Process-Relational Philosophy</a></td>
<td markdown="span"> &nbsp;— C. Robert Mesle</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/253799.The_Aims_of_Education" target="_blank">The Aims of Education</a></td>
<td markdown="span"> &nbsp;— Alfred North Whitehead</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/440366.Adventures_of_Ideas" target="_blank">Adventures of Ideas</a></td>
<td markdown="span"> &nbsp;— Alfred North Whitehead</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/10393439-the-hegel-dictionary" target="_blank">The Hegel Dictionary</a></td>
<td markdown="span"> &nbsp;— Glenn A. Magee</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/25241.The_Philosophy_of_History" target="_blank">Philosophy of History</a></td>
<td markdown="span"> &nbsp;— G.W.F.Hegel</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/319014.The_Holographic_Universe" target="_blank">The Holographic Universe</a></td>
<td markdown="span"> &nbsp;— Michael Talbot</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/35504026-a-declaration-of-the-independence-of-cyberspace" target="_blank">A Declaration of the Independence of Cyberspace</a></td>
<td markdown="span"> &nbsp;— John Perry Barlow</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/87436.The_Hedgehog_and_the_Fox" target="_blank">The Hedgehog and the Fox</a></td>
<td markdown="span"> &nbsp;— Isaiah Berlin</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1888592.Heretical_Essays_in_the_Philosophy_of_History" target="_blank">Heretical Essays in the Philosophy of History</a></td>
<td markdown="span"> &nbsp;— Jan Patocka</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/251264.Culture_and_Anarchy" target="_blank">Culture and Anarchy</a></td>
<td markdown="span"> &nbsp;— Matthew Arnold</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/385228.On_Liberty" target="_blank">On Liberty</a></td>
<td markdown="span"> &nbsp;— John Stuart Mill</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/13470.Think_on_These_Things" target="_blank">Think on These Things</a></td>
<td markdown="span"> &nbsp;— Jiddu Krishnamurti</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/350549.The_Passions_and_the_Interests" target="_blank">The Passions and the Interests</a></td>
<td markdown="span"> &nbsp;— Albert O. Hirschman</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/8737.The_Last_Temptation_of_Christ" target="_blank">The Last Temptation of Christ</a></td>
<td markdown="span"> &nbsp;— Nikos Kazantzakis</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/203100.Speed_and_Politics" target="_blank">Speed and Politics</a></td>
<td markdown="span"> &nbsp;— Paul Virilio</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/7171525-battling-to-the-end" target="_blank">Battling to the End</a></td>
<td markdown="span"> &nbsp;— René Girard</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/274826.Propaganda" target="_blank">Propaganda: The Formation of Men's Attitudes</a></td>
<td markdown="span"> &nbsp;— Jacques Ellul</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/751683.Totality_and_Infinity" target="_blank">Totality and Infinity: An Essay on Exteriority</a></td>
<td markdown="span"> &nbsp;— Emmanuel Levinas</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/710528.The_World_of_Silence" target="_blank">The World of Silence</a></td>
<td markdown="span"> &nbsp;— Max Picard</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/750481.Man_and_Technics" target="_blank">Man and Technics</a></td>
<td markdown="span"> &nbsp;— Oswald Spengler</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/883405.Bartlett_s_Familiar_Quotations" target="_blank">Bartlett's Familiar Quotations</a></td>
<td markdown="span"> &nbsp;— John Bartlett</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/70561.The_Gulag_Archipelago_1918_1956" target="_blank">The Gulag Archipelago 1918–1956</a></td>
<td markdown="span"> &nbsp;— Aleksandr Solzhenitsyn</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/6683549-you-are-not-a-gadget" target="_blank">You Are not a Gedget</a></td>
<td markdown="span"> &nbsp;— Jaron Lanier</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/2964389-understanding-gregory-bateson" target="_blank">Understanding Gregory Bateson</a></td>
<td markdown="span"> &nbsp;— Noel G. Charlton</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/656.War_and_Peace" target="_blank">War and Peace</a></td>
<td markdown="span"> &nbsp;— Leo Tolstoy</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/658.The_Kingdom_of_God_Is_Within_You" target="_blank">The Kingdom of God Is Within You</a></td>
<td markdown="span"> &nbsp;— Leo Tolstoy</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/22238497-accounting-for-the-numberphobic" target="_blank">Accounting for the Numberphobic</a></td>
<td markdown="span"> &nbsp;— Dawn Fotopulous</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/48573831-the-coming-of-neo-feudalism" target="_blank">The Coming of Neo-Feudalism</a></td>
<td markdown="span"> &nbsp;— Joel Kotkin</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/87445.Three_Critics_of_the_Enlightenment" target="_blank">Three Critics of the Enlightenment - Vico, Hamann, Herder</a></td>
<td markdown="span"> &nbsp;— Isaiah Berlin</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/337517.Things_Hidden_Since_the_Foundation_of_the_World" target="_blank">Things Hidden Since the Foundation of the World</a></td>
<td markdown="span"> &nbsp;— René Girard</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/223416.The_Right_to_Useful_Unemployment_and_Its_Professional_Enemies" target="_blank">The Right to Useful Unemployment and its Professional Enemies</a></td>
<td markdown="span"> &nbsp;— Ivan Illich</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/26097555-breaking-smart---season-1" target="_blank">Breaking Smart</a></td>
<td markdown="span"> &nbsp;— Venkatesh G. Rao</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/22392740-a-free-man-s-worship" target="_blank">A Free Man's Worship</a></td>
<td markdown="span"> &nbsp;— Bertrand Russell</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/231608.Albert_Einstein" target="_blank">Albert Einstein</a></td>
<td markdown="span"> &nbsp;— Albrecht Fölsing</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/25335482-anti-education" target="_blank">Anti-Education</a></td>
<td markdown="span"> &nbsp;— Friedrich N.</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/20492549-boundaries-of-order" target="_blank">Boundaries of Order</a></td>
<td markdown="span"> &nbsp;— Butler D. Shaffer</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/34466958-bullshit-jobs" target="_blank">Bullshit Jobs: A Theory</a></td>
<td markdown="span"> &nbsp;— David Graeber</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/178788.The_China_Study" target="_blank">The China Study</a></td>
<td markdown="span"> &nbsp;— Colin T. Campbell</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/36556202-the-coddling-of-the-american-mind" target="_blank">The Coddling of the American Mind</a></td>
<td markdown="span"> &nbsp;— Jonathan Haidt</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/33616474-the-coming-world-civilization" target="_blank">The Coming World Civilization</a></td>
<td markdown="span"> &nbsp;— William Ernest Hocking</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/series/237005-commentaries-on-living" target="_blank">Commentaries on Living Vol.I-III</a></td>
<td markdown="span"> &nbsp;— Jiddu Krishnamurti</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/640765.The_Concept_of_the_Political" target="_blank">The Concept of the Political</a></td>
<td markdown="span"> &nbsp;— Carl Schmitt</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/61554.Conjectures_and_Refutations" target="_blank">Conjectures and Refutations</a></td>
<td markdown="span"> &nbsp;— Karl Popper</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/573045.The_Crowd" target="_blank">The Crowd: A Study of the Popular Mind</a></td>
<td markdown="span"> &nbsp;— Gustave Le Bon</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1607692.The_Disinherited_Mind" target="_blank">The Disinherited Mind</a></td>
<td markdown="span"> &nbsp;— Erich Heller</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/3012579-war-and-christianity" target="_blank">War and Christianity</a></td>
<td markdown="span"> &nbsp;— Vladimir Solovyov</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/4229026-divine-sophia" target="_blank">Divine Sophia</a></td>
<td markdown="span"> &nbsp;— Vladimir Solovyov</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/3836.Don_Quixote" target="_blank">Don Quixote</a></td>
<td markdown="span"> &nbsp;— Miguel de Cervantes Saavedra</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/225850.Dumbing_Us_Down" target="_blank">Dumbing Us Down</a></td>
<td markdown="span"> &nbsp;— John Taylor Gatto</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/9519944-early-retirement-extreme" target="_blank">Early Retirement Extreme</a></td>
<td markdown="span"> &nbsp;— Jacob Lund Fisker</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/326679.Emile_or_On_Education" target="_blank">Emile, or On Education</a></td>
<td markdown="span"> &nbsp;— Jean Jacques Rousseau</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/25491.Escape_from_Freedom" target="_blank">Escape from Freedom</a></td>
<td markdown="span"> &nbsp;— Erich Fromm</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/5976571-essays-of-schopenhauer" target="_blank">Essays of Schopenhauer</a></td>
<td markdown="span"> &nbsp;— Arthur Schopenhauer</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/7684915-the-genesis-of-desire" target="_blank">The Genesis of Desire</a></td>
<td markdown="span"> &nbsp;— Jean-Michel Oughourlian</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/99944.The_Bhagavad_Gita" target="_blank">The Bhagavad Gita</a></td>
<td markdown="span"> &nbsp;— Krishna-Dwaipayana Vyasa</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/41715734-designing-japan" target="_blank">Designing Japan</a></td>
<td markdown="span"> &nbsp;— Kenya Hara</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/110763.The_Gnostic_Gospels" target="_blank">The Gnostic Gospels</a></td>
<td markdown="span"> &nbsp;— Elaine Pagels</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/2026504.Goethe_s_World_View" target="_blank">Goethe's World View</a></td>
<td markdown="span"> &nbsp;— Rudolf Steiner</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/730139.Gravity_and_Grace" target="_blank">Gravity and Grace</a></td>
<td markdown="span"> &nbsp;— Simone Weil</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/345702.The_Greeks_and_Greek_Civilization" target="_blank">The Greeks and Greek Civilization</a></td>
<td markdown="span"> &nbsp;— Jacob Burckhardt</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/295001.The_High_Price_of_Materialism" target="_blank">The High Price of Materialism</a></td>
<td markdown="span"> &nbsp;— Tim Kasser</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/243685.A_History_of_Western_Philosophy" target="_blank">A History of Western Philosophy</a></td>
<td markdown="span"> &nbsp;— Bertrand Russell</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/451565.Human_All_Too_Human" target="_blank">Human, All Too Human: A Book for Free Spirits</a></td>
<td markdown="span"> &nbsp;— Friedrich N.</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/20696000-the-hundred-year-marathon" target="_blank">The Hundred-Year Marathon</a></td>
<td markdown="span"> &nbsp;— Michael Pillsbury</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/5665.Ideas_Have_Consequences" target="_blank">Ideas Have Consequences</a></td>
<td markdown="span"> &nbsp;— Richard M. Weaver</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/33268384-igen" target="_blank">iGen</a></td>
<td markdown="span"> &nbsp;— Jean M. Twenge</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/111113.Interaction_of_Color" target="_blank">Interaction of Color</a></td>
<td markdown="span"> &nbsp;— Josef Albers</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/116913.Introduction_to_the_Reading_of_Hegel" target="_blank">Introduction to the Reading of Hegel</a></td>
<td markdown="span"> &nbsp;— Alexander Kojève</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/8885868-it-s-the-way-you-say-it" target="_blank">It's the Way You Say It</a></td>
<td markdown="span"> &nbsp;— Carol A. Fleming</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/60376.Japanese_Death_Poems" target="_blank">Japanese Death Poems</a></td>
<td markdown="span"> &nbsp;— Yoel Hoffmann</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/11545851-japanese-fashion-designers" target="_blank">Japanese Fashion Designers</a></td>
<td markdown="span"> &nbsp;— Bonnie English</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/44824750-kenya-hara" target="_blank">Designing Japan</a></td>
<td markdown="span"> &nbsp;— Kenya Hara</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/143881.Krishnamurtis_Notebook" target="_blank">Krishnamurti‘s Notebook</a></td>
<td markdown="span"> &nbsp;— Jiddu Krishnamurti</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/7489557-letters-of-oswald-spengler" target="_blank">Letters of Oswald Spengler: 1913-1936</a></td>
<td markdown="span"> &nbsp;— Oswald Spengler</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/591353.Life_Ahead" target="_blank">Life Ahead</a></td>
<td markdown="span"> &nbsp;— Jiddu Krishnamurti</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/32832.The_Lighthouse_at_the_End_of_the_World" target="_blank">The Lighthouse at the End of the World</a></td>
<td markdown="span"> &nbsp;— Jules Verne</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1229385.Living_Time_and_the_Integration_of_the_Life" target="_blank">Living Time and the Integration of the Life</a></td>
<td markdown="span"> &nbsp;— Maurice Nicoll</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/874923.Love_in_the_Western_World" target="_blank">Love in the Western World</a></td>
<td markdown="span"> &nbsp;— Denis de Rougemont</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/355273.Lives_in_the_Shadow_with_J_Krishnamurti" target="_blank">Lives in the Shadow with J. Krishnamurti</a></td>
<td markdown="span"> &nbsp;— Radha Rajagopal Sloss</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/343900.Meaning_in_History" target="_blank">Meaning in History</a></td>
<td markdown="span"> &nbsp;— Karl Löwith</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/25958.The_Medium_and_the_Light" target="_blank">The Medium and the Light</a></td>
<td markdown="span"> &nbsp;— Marshall McLuhan</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/53526.The_Mystique_of_Enlightenment" target="_blank">The Mystique of Enlightenment</a></td>
<td markdown="span"> &nbsp;— U.G.Krishnamurti</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/3420140-nature" target="_blank">Nature</a></td>
<td markdown="span"> &nbsp;— Ralph Waldo Emerson</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/398200.Representative_Men" target="_blank">Representative Men</a></td>
<td markdown="span"> &nbsp;— Ralph Waldo Emerson</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/9491855-why-the-west-rules-for-now" target="_blank">Why the West Rules—for Now</a></td>
<td markdown="span"> &nbsp;— Ian Morris</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/103625.On_Creativity" target="_blank">On Creativity</a></td>
<td markdown="span"> &nbsp;— David Bohm</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/103625.On_Creativity" target="_blank">On Dialogue</a></td>
<td markdown="span"> &nbsp;— David Bohm</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/932408.On_the_Advantage_and_Disadvantage_of_History_for_Life" target="_blank">On the Advantage and Disadvantage of History for Life</a></td>
<td markdown="span"> &nbsp;— Friedrich N.</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/177160.One_Taste" target="_blank">One Taste</a></td>
<td markdown="span"> &nbsp;— Ken Wilber</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1380489.Oration_on_the_Dignity_of_Man" target="_blank">Oration on the Dignity of Man</a></td>
<td markdown="span"> &nbsp;— Giovanni Pico della Mirandola</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/15997.Paradise_Lost" target="_blank">Paradise Lost</a></td>
<td markdown="span"> &nbsp;— John Milton</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/138144.Paradise_Regained" target="_blank">Paradise Regained</a></td>
<td markdown="span"> &nbsp;— John Milton</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/586992.The_Passion_of_the_Western_Mind" target="_blank">The Passion of the Western Mind</a></td>
<td markdown="span"> &nbsp;— Richard Tarnas</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/679913.Persecution_and_the_Art_of_Writing" target="_blank">Persecution and the Art of Writing</a></td>
<td markdown="span"> &nbsp;— Leo Strauss</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/19467599-the-philosophy-of-freedom" target="_blank">The Philosophy of Freedom</a></td>
<td markdown="span"> &nbsp;— Rudolf Steiner</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/944652.Poor_Charlie_s_Almanack" target="_blank">Poor Charlie's Almanack</a></td>
<td markdown="span"> &nbsp;— Charles T. Munger</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/287804.The_Present_Age" target="_blank">The Present Age</a></td>
<td markdown="span"> &nbsp;— Søren Kierkegaard</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/series/150106-gurdjieff-y-ouspensky" target="_blank">Psychological Commentaries Vol.I-V</a></td>
<td markdown="span"> &nbsp;— Maurice Nicoll</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/552494.The_Psychology_of_Man_s_Possible_Evolution" target="_blank">The Psychology of Man's Possible Evolution</a></td>
<td markdown="span"> &nbsp;— Maurice Nicoll</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/24966.Provocations" target="_blank">Provocations</a></td>
<td markdown="span"> &nbsp;— Søren Kierkegaard</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/342847.Pure_Immanence" target="_blank">Pure Immanence: Essays on a Life</a></td>
<td markdown="span"> &nbsp;— Gilles Deleuze</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/125974.Purity_of_Heart_is_to_Will_One_Thing" target="_blank">Purity of Heart is to Will One Thing</a></td>
<td markdown="span"> &nbsp;— Søren Kierkegaard<</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/371184.The_Reflexive_Universe" target="_blank">The Reflexive Universe</a></td>
<td markdown="span"> &nbsp;— Arthur M. Young</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/331332.Religion_and_Nothingness" target="_blank">Religion and Nothingness</a></td>
<td markdown="span"> &nbsp;— Keiji Nishitani</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/15823873-ren-girard-s-mimetic-theory" target="_blank">René Girard's Mimetic Theory</a></td>
<td markdown="span"> &nbsp;— Wolfgang Palaver</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/12562312-the-return-to-the-mystical" target="_blank">The Return to the Mystical</a></td>
<td markdown="span"> &nbsp;— Peter Tyler</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/8493026-the-philosophy-book" target="_blank">The Philosophy Book</a></td>
<td markdown="span"> &nbsp;— Will Buckingham</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/282447.The_Revolt_of_the_Masses" target="_blank">The Revolt of the Masses</a></td>
<td markdown="span"> &nbsp;— José Ortega y Gasset</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/7015920-the-riddles-of-philosophy" target="_blank">The Riddles of Philosophy</a></td>
<td markdown="span"> &nbsp;— Rudolf Steiner</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/569376.Rudolf_Steiner" target="_blank">Rudolf Steiner</a></td>
<td markdown="span"> &nbsp;— Gary Lachman</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1052.The_Richest_Man_in_Babylon" target="_blank">The Richest Man in Babylon</a></td>
<td markdown="span"> &nbsp;— George S. Clason</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/103626.Science_Order_and_Creativity" target="_blank">Science, Order and Creativity</a></td>
<td markdown="span"> &nbsp;— David Bohm</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/44290616-seeing-through-the-world" target="_blank">Seeing Through the World: Jean Gebser</a></td>
<td markdown="span"> &nbsp;— Jeremy D. Johnson</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1995421.Seeking_Wisdom" target="_blank">Seeking Wisdom</a></td>
<td markdown="span"> &nbsp;— Peter Bevelin</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/10134092-selected-essays" target="_blank">Selected Essays</a></td>
<td markdown="span"> &nbsp;— Oswald Spengler</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/8606533-selfhood-and-sacrifice" target="_blank">Selfhood and Sacrifice: René Girard and Charles Taylor</a></td>
<td markdown="span"> &nbsp;— Andrew O‘Shea</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/123845.Self_Reliance_and_Other_Essays" target="_blank">Self-Reliance and Other Essays</a></td>
<td markdown="span"> &nbsp;— Ralph Waldo Emerson</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/36064445-skin-in-the-game" target="_blank">Skin in the Game</a></td>
<td markdown="span"> &nbsp;— N.N.Taleb</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/82256.The_Sovereign_Individual" target="_blank">The Sovereign Individual</a></td>
<td markdown="span"> &nbsp;— James Dale Davidson</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/39685775-spiral-dynamics-in-action" target="_blank">Spiral Dynamics in Action</a></td>
<td markdown="span"> &nbsp;— Don Edward Beck</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/728055.Spiral_Dynamics_Integral" target="_blank">Spiral Dynamics Integral</a></td>
<td markdown="span"> &nbsp;— Don Edward Beck</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/204687.Spiral_Dynamics" target="_blank">Spiral Dynamics</a></td>
<td markdown="span"> &nbsp;— Don Edward Beck</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/117586.Studies_in_Pessimism" target="_blank">Studies in Pessimism: The Essays</a></td>
<td markdown="span"> &nbsp;— Arthur Schopenhauer</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/157129.The_Sufi_Path_Of_Knowledge" target="_blank">The Sufi Path Of Knowledge</a></td>
<td markdown="span"> &nbsp;— William C. Chittick</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/10238.The_Tao_of_Physics" target="_blank">The Tao of Physics</a></td>
<td markdown="span"> &nbsp;— Fritjof Capra</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/7962408-a-taste-of-life" target="_blank">A Taste of Life: The Last Days of U.G.K.</a></td>
<td markdown="span"> &nbsp;— Mahesh Bhatt</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/530910.Tertium_Organum" target="_blank">Tertium Organum</a></td>
<td markdown="span"> &nbsp;— P.D.Ouspensky</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/128838.The_Wholeness_of_Nature" target="_blank">The Wholeness of Nature</a></td>
<td markdown="span"> &nbsp;— Henri Bortoft</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/223929.Thinking_Architecture" target="_blank">Thinking Architecture</a></td>
<td markdown="span"> &nbsp;— Peter Zumthor</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/23948433-profit-first" target="_blank">Profit First</a></td>
<td markdown="span"> &nbsp;— Mike Michalowicz</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/204527.Thought_as_a_System" target="_blank">Thought as a System</a></td>
<td markdown="span"> &nbsp;— David Bohm</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/51893.Thus_Spoke_Zarathustra" target="_blank">Thus Spoke Zarathustra</a></td>
<td markdown="span"> &nbsp;— Friedrich N.</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/159788.Timaeus_and_Critias" target="_blank">Timaeus and Critias</a></td>
<td markdown="span"> &nbsp;— Plato</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/9677435-etica-nicomachea" target="_blank">Etica nicomachea</a></td>
<td markdown="span"> &nbsp;— Aristotle</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/2631984-the-time-paradox" target="_blank">The Time Paradox</a></td>
<td markdown="span"> &nbsp;— Philip G. Zimbardo</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/634163.To_Double_Business_Bound" target="_blank">To Double Business Bound</a></td>
<td markdown="span"> &nbsp;— René Girard<</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/51526.Too_Soon_Old_Too_Late_Smart" target="_blank">Too Soon Old, Too Late Smart</a></td>
<td markdown="span"> &nbsp;— Gordon Livingston</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/143878.Total_Freedom" target="_blank">Total Freedom</a></td>
<td markdown="span"> &nbsp;— Jiddu Krishnamurti</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/16902.Walden" target="_blank">Walden</a></td>
<td markdown="span"> &nbsp;— Henri David Thoreau</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/116020.Walden_Civil_Disobedience" target="_blank">Civil Disobedience</a></td>
<td markdown="span"> &nbsp;— Henri David Thoreau</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/6545885-white" target="_blank">White</a></td>
<td markdown="span"> &nbsp;— Kenya Hara</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/15775046-the-wizards-of-ozymandias" target="_blank">The Wizards of Ozymandias</a></td>
<td markdown="span"> &nbsp;— Butler Shaffer</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/7816424-the-world-in-2050" target="_blank">The World in 2050</a></td>
<td markdown="span"> &nbsp;— Laurence C. Smith</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/590140.The_Meaning_of_Love" target="_blank">The Meaning of Love</a></td>
<td markdown="span"> &nbsp;— Vladimir Solovyov</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/649615.War_Progress_and_the_End_of_History" target="_blank">War, Progress, and the End of History</a></td>
<td markdown="span"> &nbsp;— Vladimir Solovyov</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/274839.Anarchy_and_Christianity" target="_blank">Anarchy and Christianity</a></td>
<td markdown="span"> &nbsp;— Jacques Ellul</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/15864830-taking-appearance-seriously" target="_blank">Taking Appearance Seriously</a></td>
<td markdown="span"> &nbsp;— Henri Bortoft</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/126639.The_Heart_of_Matter" target="_blank">The Heart of Matter</a></td>
<td markdown="span"> &nbsp;— Pierre Teilhard de Chardin</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/9543845-the-laws-of-imitation" target="_blank">The Laws of Imitation</a></td>
<td markdown="span"> &nbsp;— Gabriel Tarde</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1210655.The_Heart_of_Prajna_Paramita_Sutra" target="_blank">The Heart of Prajna Paramita Sutra</a></td>
<td markdown="span"> &nbsp;—</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/25698.An_Inquiry_into_the_Nature_and_Causes_of_the_Wealth_of_Nations" target="_blank">An Inquiry into the Nature and Causes of the Wealth of Nations</a></td>
<td markdown="span"> &nbsp;— Adam Smith</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/642679.Karl_Marx" target="_blank">Karl Marx: His Life and Environment</a></td>
<td markdown="span"> &nbsp;— Isaiah Berlin</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/25673.City_of_God" target="_blank">City of God</a></td>
<td markdown="span"> &nbsp;— Augustine of Hippo</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/3873.A_History_of_God" target="_blank">A History of God</a></td>
<td markdown="span"> &nbsp;— Karen Armstrong</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/13530973-antifragile" target="_blank">Antifragile</a></td>
<td markdown="span"> &nbsp;— N.N.Taleb</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/3023.Basic_Economics" target="_blank">Basic Economics</a></td>
<td markdown="span"> &nbsp;— Thomas Sowell</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/44045.A_Universal_History_of_Iniquity" target="_blank">A Universal History of Iniquity</a></td>
<td markdown="span"> &nbsp;— Jorge Luis Borges</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/660518.Better_Never_to_Have_Been" target="_blank">Better Never to Have Been</a></td>
<td markdown="span"> &nbsp;— David Benatar</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1120042.Bohm_Biederman_Correspondence" target="_blank">Bohm-Biederman Correspondence</a></td>
<td markdown="span"> &nbsp;— David Bohm<</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/154409.Bureaucracy" target="_blank">Bureaucracy</a></td>
<td markdown="span"> &nbsp;— Ludwig von Mises</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/43708933-the-cognitive-theoretic-model-of-the-universe" target="_blank">The Cognitive-Theoretic Model of the Universe</a></td>
<td markdown="span"> &nbsp;— Chris Langan</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/797329.Maxims" target="_blank">Maxims</a></td>
<td markdown="span"> &nbsp;— François de La Rochefoucauld</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/25852512-the-collected-poems-of-william-blake" target="_blank">The Collected Poems</a></td>
<td markdown="span"> &nbsp;— William Blake</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/17802065-hyperobjects" target="_blank">Hyperobjects</a></td>
<td markdown="span"> &nbsp;— Timothy Morton</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/307468.Graphs_Maps_Trees" target="_blank">Graphs, Maps, Trees</a></td>
<td markdown="span"> &nbsp;— Franco Moretti</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/242319.I_See_Satan_Fall_Like_Lightning" target="_blank">I See Satan Fall Like Lightning</a></td>
<td markdown="span"> &nbsp;— René Girard</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/30739587-lonely-planet-bolivia" target="_blank">Bolivia</a></td>
<td markdown="span"> &nbsp;— Lonely Planet</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/8470719-the-selected-poetry-of-robinson-jeffers" target="_blank">Selected Poetry</a></td>
<td markdown="span"> &nbsp;— Robinson Jeffers</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/420330.The_Fable_of_the_Bees_and_Other_Writings" target="_blank">The Fable of the Bees</a></td>
<td markdown="span"> &nbsp;— Bernard Mandeville</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/440463.The_Gutenberg_Galaxy" target="_blank">The Gutenberg Galaxy</a></td>
<td markdown="span"> &nbsp;— Marshall McLuhan</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/837326.The_Idea_Of_Progress_An_Inquiry_Into_Its_Origin_And_Growth" target="_blank">The Idea Of Progress</a></td>
<td markdown="span"> &nbsp;— J.B.Burt</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/203092.The_Information_Bomb" target="_blank">The Information Bomb</a></td>
<td markdown="span"> &nbsp;— Paul Virilio</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/456240.The_Japanese_Way_of_Tea" target="_blank">The Japanese Way of Tea</a></td>
<td markdown="span"> &nbsp;— Sōshitsu Sen XV</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/14469631-the-kant-dictionary" target="_blank">The Kant Dictionary</a></td>
<td markdown="span"> &nbsp;— Lucas Thorpe</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/13591971-h-lderlin-kleist-and-nietzsche" target="_blank">The Struggle with the Daemon</a></td>
<td markdown="span"> &nbsp;— Stefan Zweig</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/498337.The_Time_Falling_Bodies_Take_To_Light" target="_blank">The Time Falling Bodies Take To Light</a></td>
<td markdown="span"> &nbsp;— William Irwin Thompson</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/821987.Weaving_the_Web" target="_blank">Weaving the Web</a></td>
<td markdown="span"> &nbsp;— Tim Berners-Lee</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/86108.Weakening_Philosophy" target="_blank">Weakening Philosophy</a></td>
<td markdown="span"> &nbsp;— Santiago Zabala</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/26252.The_Enneads" target="_blank">The Enneads</a></td>
<td markdown="span"> &nbsp;— Plotinus</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/205218.Ethics" target="_blank">Ethics</a></td>
<td markdown="span"> &nbsp;— Baruch Spinoza</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/208657.Theological_Political_Treatise" target="_blank">Theological-Political Treatise</a></td>
<td markdown="span"> &nbsp;— Baruch Spinoza</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/2226656.The_Ecology_of_Wisdom" target="_blank">The Ecology of Wisdom</a></td>
<td markdown="span"> &nbsp;— Arne Naess</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1074849.Ecology_Community_and_Lifestyle" target="_blank">Ecology, Community and Lifestyle</a></td>
<td markdown="span"> &nbsp;— Arne Naess</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/117031.On_War" target="_blank">On War</a></td>
<td markdown="span"> &nbsp;— Carl von Clausewitz</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/251001.Cosmopolitanism" target="_blank">Cosmopolitanism</a></td>
<td markdown="span"> &nbsp;— Kwame Anthony Appiah</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/45035203-technological-slavery" target="_blank">Technological Slavery</a></td>
<td markdown="span"> &nbsp;— T.J. Kaczynski</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/160019.Reflections_on_the_Revolution_in_France" target="_blank">Reflections on the Revolution in France</a></td>
<td markdown="span"> &nbsp;— Edmund Burke;</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/59503518-edmund-burke-on-taste-on-the-sublime-and-beautiful-reflections-on-the" target="_blank">On Taste, On the Sublime and Beautiful</a></td>
<td markdown="span"> &nbsp;— Edmund Burke</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/451553.Untimely_Meditations" target="_blank">Untimely Meditations</a></td>
<td markdown="span"> &nbsp;— Friedrich N.</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/141352.A_Hunger_Artist" target="_blank">A Hunger Artist</a></td>
<td markdown="span"> &nbsp;— Franz Kafka</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/6762192-essays-and-letters" target="_blank">Essays and Letters</a></td>
<td markdown="span"> &nbsp;— Friedrich Hölderlin</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/323727.New_Science" target="_blank">Scienza Nuova</a></td>
<td markdown="span"> &nbsp;— Giambattista Vico</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/323728.On_the_Study_Methods_of_Our_Time" target="_blank">On the Study Methods of Our Time</a></td>
<td markdown="span"> &nbsp;— Giambattista Vico</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/29632313-the-collected-works-of-john-stuart-mill" target="_blank">Collected Works</a></td>
<td markdown="span"> &nbsp;— John Stuart Mill</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/148489.The_Essence_of_Religion" target="_blank">The Essence of Religion</a></td>
<td markdown="span"> &nbsp;— Ludwig Feuerbach</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/148488.The_Essence_of_Christianity" target="_blank">The Essence of Christianity</a></td>
<td markdown="span"> &nbsp;— Ludwig Feuerbach</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/257146.What_is_Called_Thinking" target="_blank">What is Called Thinking?</a></td>
<td markdown="span"> &nbsp;— Martin Heidegger</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/19290658-the-heidegger-dictionary" target="_blank">Heidegger Dictionary</a></td>
<td markdown="span"> &nbsp;— Daniel O. Dahlstrom</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/300448.Tears_and_Saints?ac=1&from_search=true&qid=EHCg2NtszJ&rank=1" target="_blank">Tears and Saints</a></td>
<td markdown="span"> &nbsp;— Emil M. Cioran</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/843433.Philosophy?ac=1&from_search=true&qid=HmrsnclYGm&rank=1" target="_blank">Philosophy: Who Needs It</a></td>
<td markdown="span"> &nbsp;— Ayn Rand</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/665.The_Virtue_of_Selfishness?ac=1&from_search=true&qid=mqeMO0o3Ne&rank=1" target="_blank">The Virtue of Selfishness</a></td>
<td markdown="span"> &nbsp;— Ayn Rand</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/135742.In_Praise_of_Idleness_and_Other_Essays?ac=1&from_search=true&qid=jpvUi7mHnm&rank=1" target="_blank">In Praise of Idleness</a></td>
<td markdown="span"> &nbsp;— Bertrand Russell</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/824412.A_Secular_Age?ac=1&from_search=true&qid=VzjYXAMhml&rank=1" target="_blank">A Secular Age</a></td>
<td markdown="span"> &nbsp;— Charles Taylor</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/117564.The_Trouble_with_Being_Born?ac=1&from_search=true&qid=NYAHKLoQBn&rank=1" target="_blank">The Trouble with Being Born</a></td>
<td markdown="span"> &nbsp;— Emil M. Cioran</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/2855.A_Short_History_of_Decay" target="_blank">A Short History of Decay</a></td>
<td markdown="span"> &nbsp;— Emil M. Cioran</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/300447.Anathemas_and_Admirations" target="_blank">Anathemas and Admirations</a></td>
<td markdown="span"> &nbsp;— Emil M. Cioran</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/455488.History_and_Utopia" target="_blank">History and Utopia</a></td>
<td markdown="span"> &nbsp;— Emil M. Cioran</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/80311.A_Treatise_of_Human_Nature?ac=1&from_search=true&qid=bsJWEPaIEa&rank=1" target="_blank">A Treatise of Human Nature</a></td>
<td markdown="span"> &nbsp;— David Hume</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/25708.Saint_Thomas_Aquinas?ac=1&from_search=true&qid=IWvWoXctuF&rank=3" target="_blank">Saint Thomas Aquinas</a></td>
<td markdown="span"> &nbsp;— G.K.Chesterton</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/159994.A_Treatise_Concerning_the_Principles_of_Human_Knowledge" target="_blank">Principles of Human Knowledge</a></td>
<td markdown="span"> &nbsp;— George Berkeley</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/3339527-all-art-is-propaganda" target="_blank">All Art is Propaganda</a></td>
<td markdown="span"> &nbsp;— George Orwell</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/21874649-passions" target="_blank">Passions</a></td>
<td markdown="span"> &nbsp;— Giacomo Leopard</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/85826.Homo_Sacer" target="_blank">Homo Sacer</a></td>
<td markdown="span"> &nbsp;— Giorgio Agamben</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/396931.The_Origins_of_Totalitarianism" target="_blank">The Origins of Totalitarianism</a></td>
<td markdown="span"> &nbsp;— Hannah Arendt</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/710015.Laughter" target="_blank">Laughter</a></td>
<td markdown="span"> &nbsp;— Henri Bergson</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/84707.Russian_Thinkers" target="_blank">Russian Thinkers</a></td>
<td markdown="span"> &nbsp;— Isaiah Berlin</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/84713.The_Roots_of_Romanticism?ac=1&from_search=true&qid=fZqnZp8L8w&rank=1" target="_blank">The Roots of Romanticism</a></td>
<td markdown="span"> &nbsp;— Isaiah Berlin</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/595228.Vico_and_Herder?ac=1&from_search=true&qid=YzExkOrkcz&rank=1" target="_blank">Vico and Herder</a></td>
<td markdown="span"> &nbsp;— Isaiah Berlin</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/3509490-against-pure-reason" target="_blank">Against Pure Reason</a></td>
<td markdown="span"> &nbsp;— J.G.Herder</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/16773954-herder?ac=1&from_search=true&qid=ekOyi9QLbT&rank=1" target="_blank">Philosophical Writings</a></td>
<td markdown="span"> &nbsp;— J.G.Herder</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/847863.Conversations_of_Goethe" target="_blank">Conversations of Goethe</a></td>
<td markdown="span"> &nbsp;— J.P.Eckermann</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/419153.Abuse_of_Language_Abuse_of_Power?ac=1&from_search=true&qid=FcdhepLs4Z&rank=1" target="_blank">Abuse of Language, Abuse of Power</a></td>
<td markdown="span"> &nbsp;— Josef Pieper</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/568864.The_Conservative_Mind?ac=1&from_search=true&qid=Rtv8F303qD&rank=1" target="_blank">The Conservative Mind</a></td>
<td markdown="span"> &nbsp;— Russell Kirk</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/22511969-how-to-be-a-conservative" target="_blank">How to Be a Conservative</a></td>
<td markdown="span"> &nbsp;— Roger Scruton</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/26072982-conversations-with-roger-scruton?ac=1&from_search=true&qid=nOQhJVoulL&rank=1" target="_blank">Conversations with Roger Scruton</a></td>
<td markdown="span"> &nbsp;— Mark Dooley</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/6323955-beauty" target="_blank">Beauty</a></td>
<td markdown="span"> &nbsp;— Roger Scruton</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1344740.From_Hegel_to_Nietzsche?ac=1&from_search=true&qid=wo8hDNb2iq&rank=1" target="_blank">From Hegel to N</a></td>
<td markdown="span"> &nbsp;— Karl Löwith</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1170615.God_Locke_and_Equality?ac=1&from_search=true&qid=7e1BV0JgHc&rank=1" target="_blank">God, Locke, and Equality</a></td>
<td markdown="span"> &nbsp;— Jeremy Waldron</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/154246.The_Theory_of_Money_and_Credit?ac=1&from_search=true&qid=G33bwMVByu&rank=1" target="_blank">The Theory of Money and Credit</a></td>
<td markdown="span"> &nbsp;— Ludwig von Mises</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/945048.Degeneration?ac=1&from_search=true&qid=1otFa4OlA8&rank=3" target="_blank">Degeneration</a></td>
<td markdown="span"> &nbsp;— Max Nordau</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1353492.Rudolph_Schindler?ac=1&from_search=true&qid=GQYWLN1ov1&rank=3" target="_blank">Rudolph Schindler</a></td>
<td markdown="span"> &nbsp;— David Gebhard</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/28024.The_Sacred_and_the_Profane?ac=1&from_search=true&qid=OLkP6sEEVM&rank=1" target="_blank">The Sacred and The Profane</a></td>
<td markdown="span"> &nbsp;— Mircea Eliade</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/30733.Montaigne?ac=1&from_search=true&qid=b33vdSHl8s&rank=3" target="_blank">Essays</a></td>
<td markdown="span"> &nbsp;— Michel de Montaigne</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/28862.The_Prince?ac=1&from_search=true&qid=RT5cFyGu3j&rank=1" target="_blank">The Prince</a></td>
<td markdown="span"> &nbsp;— Niccolò Machiavelli</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/4706472-nicholas-of-cusa-s-metaphysic-of-contraction?ac=1&from_search=true&qid=qLH2RZq69J&rank=1" target="_blank">Metaphysic of Contraction</a></td>
<td markdown="span"> &nbsp;— Nicolas of Cusa</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/5119752-nicholas-of-cusa?ac=1&from_search=true&qid=mOkmNMQkSD&rank=1" target="_blank">Metaphysical Speculations</a></td>
<td markdown="span"> &nbsp;— Nicolas of Cusa</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/337182.Hymns_to_the_Night?ac=1&from_search=true&qid=Ula5GtRq3S&rank=1" target="_blank">Hymns to the Night</a></td>
<td markdown="span"> &nbsp;— Novalis</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/337177.Notes_for_a_Romantic_Encyclopaedia?ac=1&from_search=true&qid=rpcLSAp8xt&rank=1" target="_blank">Notes for a Romantic Encyclopaedia</a></td>
<td markdown="span"> &nbsp;— Novalis</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/337184.Philosophical_Writings?ac=1&from_search=true&qid=ry04mErP2k&rank=4" target="_blank">Philosophical Writings</a></td>
<td markdown="span"> &nbsp;— Novalis</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/12554522-the-disciples-at-sais-and-other-fragments?ac=1&from_search=true&qid=VnRsJUvR7t&rank=1" target="_blank">The Disciples at Sais and Other Fragments</a></td>
<td markdown="span"> &nbsp;— Novalis</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/879281.A_New_Model_of_the_Universe?ac=1&from_search=true&qid=7OwBBISfmh&rank=1" target="_blank">A New Model of the Universe</a></td>
<td markdown="span"> &nbsp;— P.D.Ouspensky</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/552494.The_Psychology_of_Man_s_Possible_Evolution?ac=1&from_search=true&qid=mfihuB5ldy&rank=1" target="_blank">The Psychology of Man‘s Possible Evolution</a></td>
<td markdown="span"> &nbsp;— P.D.Ouspensky</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/203090.The_Aesthetics_of_Disappearance?ac=1&from_search=true&qid=QJaAGoE56H&rank=1" target="_blank">The Aesthetics of Disappearance</a></td>
<td markdown="span"> &nbsp;— Paul Virilio</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/15931668-you-must-change-your-life?ac=1&from_search=true&qid=qMc6AeTvwH&rank=1" target="_blank">You Must Change Your Life</a></td>
<td markdown="span"> &nbsp;— Peter Sloterdijk</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/11336254-bubbles?ac=1&from_search=true&qid=ooJccCZ17D&rank=1" target="_blank">Bubbles: Spheres I</a></td>
<td markdown="span"> &nbsp;— Peter Sloterdijk</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/925317.An_Appeal_to_the_Young?ac=1&from_search=true&qid=X0kENFCAGb&rank=1" target="_blank">An Appeal to the Young</a></td>
<td markdown="span"> &nbsp;— Pyotr Kropotkin</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/76589.The_Divine_Milieu?ac=1&from_search=true&qid=HfGqWZmvRq&rank=1" target="_blank">The Divine Milieu</a></td>
<td markdown="span"> &nbsp;— Pierre Teilhard de Chardin</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/19240373-the-life-of-teilhard-de-chardin?ac=1&from_search=true&qid=BTbqwoSV9e&rank=2" target="_blank">The Life of Teilhard de Chardin</a></td>
<td markdown="span"> &nbsp;— R.Speaight</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/19240373-the-life-of-teilhard-de-chardin?ac=1&from_search=true&qid=BTbqwoSV9e&rank=2" target="_blank">The Future of Man</a></td>
<td markdown="span"> &nbsp;— Pierre Teilhard de Chardin</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/232567.The_Phenomenon_of_Man?ac=1&from_search=true&qid=UfZAG5sX4R&rank=1" target="_blank">The Phenomenon of Man</a></td>
<td markdown="span"> &nbsp;— Pierre Teilhard de Chardin</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/30632584-writings-in-time-of-war?ac=1&from_search=true&qid=SFuleqZMai&rank=2" target="_blank">Writings in Time of War</a></td>
<td markdown="span"> &nbsp;— Pierre Teilhard de Chardin</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/11375965-an-essay-on-the-beautiful?ac=1&from_search=true&qid=hfruUEeBT2&rank=1" target="_blank">An Essay on the Beautiful</a></td>
<td markdown="span"> &nbsp;— Plotinus</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/10374136-the-philosophy-of-progress?ac=1&from_search=true&qid=N1kuBNavlA&rank=2" target="_blank">The Philosophy of Progress</a></td>
<td markdown="span"> &nbsp;— Pierre-Joseph Proudhon</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/10374136-the-philosophy-of-progress?ac=1&from_search=true&qid=N1kuBNavlA&rank=2" target="_blank">God is Evil, Man is Free</a></td>
<td markdown="span"> &nbsp;— Pierre-Joseph Proudhon</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/4825580-the-poetry-of-rilke?ac=1&from_search=true&qid=CYTJEg83Nk&rank=2" target="_blank">The Poetry</a></td>
<td markdown="span"> &nbsp;— Rainer Maria Rilke</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/31947.Philosophy_and_the_Mirror_of_Nature?ac=1&from_search=true&qid=CVouX5QmyP&rank=1" target="_blank">Philosophy and the Mirror of Nature</a></td>
<td markdown="span"> &nbsp;— Richard Rorty</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/168725.Summa_Contra_Gentiles?ac=1&from_search=true&qid=mCLnI0Sk3P&rank=1" target="_blank">Summa Contra Gentiles</a></td>
<td markdown="span"> &nbsp;— Thomas Aquinas</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/34001144-thomas-aquinas?ac=1&from_search=true&qid=7xZttVzHLZ&rank=1" target="_blank">Disputed Questions on the Virtues</a></td>
<td markdown="span"> &nbsp;— Thomas Aquinas</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/398834.Introduction_to_the_Devout_Life?ac=1&from_search=true&qid=zqWGkHZIQ3&rank=1" target="_blank">Introduction to the Devout Life</a></td>
<td markdown="span"> &nbsp;— Francis de Sales</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/51660.Food_of_the_Gods?ac=1&from_search=true&qid=K6U5JbIDX9&rank=1" target="_blank">Food of the Gods</a></td>
<td markdown="span"> &nbsp;— Terrence McKenna</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1006826.History_of_Germany_1780_1918?ac=1&from_search=true&qid=UG9a609QeX&rank=1" target="_blank">History of Germany 1780-1918</a></td>
<td markdown="span"> &nbsp;— David Blackbourn</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/761406.Goebbels?ac=1&from_search=true&qid=PE31lQy8gA&rank=4" target="_blank">Goebbels: Mastermind of the Third Reich</a></td>
<td markdown="span"> &nbsp;— David Irving</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/99324.The_Art_of_War?ac=1&from_search=true&qid=g6x3pSslBe&rank=4" target="_blank">The Art of War</a></td>
<td markdown="span"> &nbsp;— Niccolo Machiavelli</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/12444229-rerum-novarum?ac=1&from_search=true&qid=tTtMtQ9sUb&rank=1" target="_blank">Rerum Novarum</a></td>
<td markdown="span"> &nbsp;— Pope Leo XIII</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/318236.The_French_Revolution?ac=1&from_search=true&qid=tc1Iv5GHOR&rank=1" target="_blank">The French Revolution, a History</a></td>
<td markdown="span"> &nbsp;— Thomas Carlyle</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/854577.Zen_and_the_Birds_of_Appetite?ac=1&from_search=true&qid=TeRvkkrtsT&rank=1" target="_blank">Zen and the Birds of Appetite</a></td>
<td markdown="span"> &nbsp;— Thomas Merton</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/420553.The_Intimate_Merton?ac=1&from_search=true&qid=H0Fa0TdGJ3&rank=1" target="_blank">The Intimate Merton</a></td>
<td markdown="span"> &nbsp;— Thomas Merton</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1031803.The_Age_of_Reason?ac=1&from_search=true&qid=xAA2YWBKpV&rank=3" target="_blank">The Age of Reason</a></td>
<td markdown="span"> &nbsp;— Thomas Paine</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/3930193-democracy-is-self-government?ac=1&from_search=true&qid=C42JL9Our4&rank=1" target="_blank">Democracy Is Self-Government</a></td>
<td markdown="span"> &nbsp;— Harold W. Percival</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1637466.Thinking_Destiny" target="_blank">Thinking & Destiny</a></td>
<td markdown="span"> &nbsp;— Harold W. Percival</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/707387.The_American_Replacement_of_Nature?ac=1&from_search=true&qid=cKFkEJbhMX&rank=1" target="_blank">The American Replacement of Nature</a></td>
<td markdown="span"> &nbsp;— William Irwin Thompson</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/155241.Voices_of_Silence?ac=1&from_search=true&qid=uOBSHhGA77&rank=1" target="_blank">Lives of the Trappists Today</a></td>
<td markdown="span"> &nbsp;— Frank Bianco</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/6361898-the-law" target="_blank">The Law</a></td>
<td markdown="span"> &nbsp;— Frédéric Bastiat</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/833807.Roget_s_International_Thesaurus" target="_blank">Roget's International Thesaurus </a></td>
<td markdown="span"> &nbsp;— Peter Mark Roget</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/25182012-a-short-history-of-man" target="_blank">A Short History of Man: Progress and Decline </a></td>
<td markdown="span"> &nbsp;— Hans-Hermann Hoppe</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/7717046-natural-elites-intellectuals-and-the-state" target="_blank">Natural Elites, Intellectuals, and the State </a></td>
<td markdown="span"> &nbsp;— Hans-Hermann Hoppe</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/32307349-the-dark-enlightenment" target="_blank">The Dark Enlightenment</a></td>
<td markdown="span"> &nbsp;— Nick Land</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/633004.Evolution" target="_blank">Evolution: A Theory In Crisis</a></td>
<td markdown="span"> &nbsp;— Michael Danton</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/25195991-meditations-on-the-divine-comedy-of-dante-alighieri" target="_blank">Meditations on the Divine Comedy of Dante Alighieri</a></td>
<td markdown="span"> &nbsp;— A.S. Kline</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/350003.The_Accursed_Share" target="_blank">The Accursed Share: An Essay on General Economy, Volume I & II</a></td>
<td markdown="span"> &nbsp;— Georges Bataille</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/829352.Analytical_Psychology_Its_Theory_and_Practice" target="_blank">Analytical Psychology, Its Theory and Practice</a></td>
<td markdown="span"> &nbsp;— C.G. Jung</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/345784.The_Thirst_for_Annihilation" target="_blank">The Thirst for Annihilation</a></td>
<td markdown="span"> &nbsp;— Nick Land</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/262404.Seeing_the_Form" target="_blank">Seeing the Form</a></td>
<td markdown="span"> &nbsp;— Hans Urs von Balthasar</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/54222022-token-economy" target="_blank">Token Economy</a></td>
<td markdown="span"> &nbsp;— Shermin Voshmgir</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/993238.Knots" target="_blank">Knots</a></td>
<td markdown="span"> &nbsp;— R.D. Laing</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/152435.Steps_to_an_Ecology_of_Mind" target="_blank">Steps to an Ecology of Mind</a></td>
<td markdown="span"> &nbsp;— Gregory Bateson</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1632125.Leftism_Revisited" target="_blank">Leftism Revisited</a></td>
<td markdown="span"> &nbsp;— Erik von Kuehnelt-Leddihn</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/25934857-a-gentle-introduction-to-unqualified-reservations" target="_blank">A Gentle Introduction to Unqualified Reservations</a></td>
<td markdown="span"> &nbsp;— Mencius Moldbug</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/74176.The_Protestant_Ethic_and_the_Spirit_of_Capitalism" target="_blank">The Protestant Ethic and the Spirit of Capitalism</a></td>
<td markdown="span"> &nbsp;— Max Weber</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/208657.Theological_Political_Treatise" target="_blank">Theological-Political Treatise</a></td>
<td markdown="span"> &nbsp;— Baruch Spinoza</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/80313.Dialogues_Concerning_Natural_Religion" target="_blank">Dialogues Concerning Natural Religion</a></td>
<td markdown="span"> &nbsp;— David Hume</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/280650.Leo_Strauss_and_the_Theologico_Political_Problem" target="_blank">Leo Strauss and the Theologico-Political Problem;</a></td>
<td markdown="span"> &nbsp;— Heinrich Meier</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1843378.The_Pure_Theory_of_Politics" target="_blank">The Pure Theory of Politics</a></td>
<td markdown="span"> &nbsp;— Bertrand De Jouvenel</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1490396.The_Ethics_of_Redistribution" target="_blank">The Ethics of Redistribution</a></td>
<td markdown="span"> &nbsp;— Bertrand De Jouvenel</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1661474.On_Power" target="_blank">On Power: The Natural History of Its Growth</a></td>
<td markdown="span"> &nbsp;— Bertrand De Jouvenel</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/386629.Sovereignty" target="_blank">Sovereignty: An Inquiry into the Political Good</a></td>
<td markdown="span"> &nbsp;— Bertrand De Jouvenel</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/2138574.Economics_and_the_Good_Life" target="_blank">Economics and the Good Life</a></td>
<td markdown="span"> &nbsp;— Bertrand De Jouvenel</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1066511.The_Twenty_Years_Crisis_1919_1939" target="_blank">The Twenty Years' Crisis, 1919-1939</a></td>
<td markdown="span"> &nbsp;— Edward Hall</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/82120.The_Worldly_Philosophers" target="_blank">The Worldly Philosophers</a></td>
<td markdown="span"> &nbsp;— Robert L. Heilbroner</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/12124340-the-turgot-collection" target="_blank">The Turgot Collection</a></td>
<td markdown="span"> &nbsp;— Anne Robert Jacques Turgot</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/464849.All_for_Love" target="_blank">All for Love</a></td>
<td markdown="span"> &nbsp;— John Dryden</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1138327.The_Works_of_John_Dryden" target="_blank">The Works of John Dryden </a></td>
<td markdown="span"> &nbsp;— John Dryden</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/30735.The_Complete_Essays" target="_blank">Essays</a></td>
<td markdown="span"> &nbsp;— Michel de Montaigne</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/146455.Chronicles_of_Bustos_Domecq" target="_blank">Chronicles of Bustos Domecq</a></td>
<td markdown="span"> &nbsp;— Jorge Luis Borges</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/42607.As_You_Like_It" target="_blank">As You Like It</a></td>
<td markdown="span"> &nbsp;— William Shakespeare</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/3096589-education" target="_blank">Education: Intellectual, Moral and Physical</a></td>
<td markdown="span"> &nbsp;— Herbert Spencer</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/677923.The_Essays" target="_blank">The Essays</a></td>
<td markdown="span"> &nbsp;— Francis Bacon</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1268994." target="_blank">For a New Liberty</a></td>
<td markdown="span"> &nbsp;— Murray N. Rothbard</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/168946.Egalitarianism_as_a_Revolt_Against_Nature_and_Other_Essays" target="_blank">Egalitarianism as a Revolt Against Nature</a></td>
<td markdown="span"> &nbsp;— Murray N. Rothbard</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/18210762-the-reckoning" target="_blank">The Reckoning: Financial Accountability and the Rise and Fall of Nations</a></td>
<td markdown="span"> &nbsp;— Jacob Soll</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/318236.The_French_Revolution" target="_blank">The French Revolution</a></td>
<td markdown="span"> &nbsp;— Thomas Carlyle</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/635773.Envy" target="_blank">Envy: A Theory of Social Behaviour</a></td>
<td markdown="span"> &nbsp;— Helmut Schoeck</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/13616002-classical-liberalism-and-the-austrian-school" target="Classical Liberalism and the Austrian School">Classical Liberalism and the Austrian School</a></td>
<td markdown="span"> &nbsp;— Ralph Raico</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/50175330-the-infinite-machine" target="_blank">The Infinite Machine</a></td>
<td markdown="span"> &nbsp;— Camila Russo</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/225468.Industrial_Society_and_Its_Future" target="_blank">Industrial Society and Its Future</a></td>
<td markdown="span"> &nbsp;— Theodore J. Kaczynski</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/448836.Second_Treatise_of_Government" target="_blank">Second Treatise of Government</a></td>
<td markdown="span"> &nbsp;— John Locke</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/6556591-the-cynic-s-breviary" target="_blank">The Cynic's Breviary</a></td>
<td markdown="span"> &nbsp;— Nicolas Chamfort</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/1687632.The_Characters_of_Jean_de_La_Bruyere" target="_blank">The Characters</a></td>
<td markdown="span"> &nbsp;— Jean de La Bruyère</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/21284241-maxims-and-thoughts" target="_blank">Maxims and Thoughts</a></td>
<td markdown="span"> &nbsp;— Luc de Clapiers de Vauvenargues</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/503150.Letters_to_a_Young_Contrarian" target="_blank">Letters to a Young Contrarian</a></td>
<td markdown="span"> &nbsp;— Christopher Hitchens</td>
</tr>
<tr>
<td markdown="span"><a href="https://www.goodreads.com/book/show/49455.Notes_from_Underground" target="_blank">Notes from Underground</a></td>
<td markdown="span"> &nbsp;— Fyodor Dostoevsky</td>
</tr>
</tbody>
</table>
</details>

<details>
  <summary>Good articles:</summary>

<table>
<colgroup>
<col width="60%" />
<col width="50%" />
</colgroup>
<tbody>
<tr>
<td markdown="span"><a href="http://tech.mit.edu/V105/N16/weisen.16n.html" target="_blank">Weizenbaum examines computers and society</a></td>
</tr>
<tr>
<td markdown="span"><a href="http://www.olearyzone.com/classes/philosophyS2/readings/goethe/StagesofMind.pdf" target="_blank">Stages of Man's Mind</a></td>
<td markdown="span"> &nbsp;— J.W.Goethe</td>
<tr>
<td markdown="span"><a href="https://bitcoin.org/bitcoin.pdf" target="_blank">Bitcoin: A Peer-to-Peer Electronic Cash System</a></td>
<td markdown="span"> &nbsp;— Satoshi Nakamoto</td>
</tr>
</tr>
</tbody>
</table>
</details>

<details>
  <summary>Good classical pieces:</summary>

<table>
<colgroup>
<col width="60%" />
<col width="50%" />
</colgroup>
<tbody>
<p>Notwithstanding the copyright breach, I’ve decided—under the overwhelming pressure of uber-law aesthetic reasons and my passion for classical music—to nonetheless share my favourite pieces:</p>
<tr>
  <td markdown="span">
    <br>
      <audio controls>
        <source src="/assets/classical-pieces/10.2. Große Sonate f++r Violine und Pianoforte op. 121, I. Ziemlich langsam - Lebhaft.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
      </audio>
    <br>
  </td>
  <td markdown="span">
    <br>
    &nbsp;— Robert Schumann
    <br>
  </td>
</tr>
<tr>
  <td markdown="span">
    <br>
      <audio controls>
        <source src="/assets/classical-pieces/Overture_Henry-Purcell.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
      </audio>
    <br>
  </td>
  <td markdown="span">
  <br>
  &nbsp;Henry Purcell — Overture
  <br>
  </td>
</tr>
<tr>
  <td markdown="span">
    <br>
      <audio controls>
        <source src="/assets/classical-pieces/Ciacona in G Minor, Z. 730_Henry-Purcell.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
      </audio>
    <br>
  </td>
  <td markdown="span">
  <br>
  &nbsp;Henry Purcell — Ciacona in G Minor, Z. 730
  <br>
  </td>
</tr>
</tbody>
</table>
</details>
