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

## Brightening people, brightening the world.

Hi, I’m Gavi — a researcher in HCI who dreams of living like a daisy.
The daisy, meaning “day’s eye,” reminds me that everyone carries a sun within.
Through my work, I hope to brighten that light in people — gently, thoughtfully.
Thanks for stopping by. Hope to cross paths at a conference someday!



</div>
