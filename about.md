---
layout: page
title: About
permalink: /about/
published: true
---

<div class="page" markdown="1">

{% capture page_subtitle %}
<img
    class="me"
    alt="{{ author.name }}"
    src="{{ site.author.photo | relative_url }}"
    srcset="{{ site.author.photo2x | relative_url }} 2x"
/>
{% endcapture %}

{% include page/title.html title=page.title subtitle=page_subtitle %}

## Hello I'm HCI reasearcher Gavi in Korea :)

Be right Be humble. This is means of my name.
I'm interested in Computer Science, Sociology, and Cognitive Science.
If you wanna 'compile' me, please contact to gocalm00@gmail.com.


</div>
