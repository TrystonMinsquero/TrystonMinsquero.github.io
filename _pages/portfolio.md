---
permalink: /portfolio/
title: Portfolio
---

<div class="pt-12" aria-hidden="true"></div>

{% include projects.html portfolio=true %}

<div class="pt-10" aria-hidden="true"></div>

<button id="show-archive" class="mx-auto display-block"> Show Archive </button>

<div class="stateful" for="show-archive">
    <div class="pt-10" aria-hidden="true"></div>
    {% include projects.html exclude-portfolio=true %}
</div>

<div class="pb-12" aria-hidden="true"></div>