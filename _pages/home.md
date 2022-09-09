---
permalink: /
title: Home

animated-title: true
---

<div class="flex flex-column lg:flex-row justify-center items-center space-evenly py-12">
    <img class='border-radius-full lg:mr-12' src='/assets/images/Me.png' alt='picture of me' style="width: 300px; height: 300px;"/>
    <p class="mt-6 lg:m-0 text-center font-lg">
        I am currently a Computer Science Student at UTD and plan on graduating in the Fall of 2022. I love problem solving and creating, so any kind of software development is perfect for me. Currently looking for a full time position starting in January of 2023, you can <a href='/about/'>read more</a> about me in my about section.
    </p>
</div>

---

<div class="ignore content-wrapper py-12">
    {% include recent-projects.html amount=3 class="content justify-between" %}
</div>