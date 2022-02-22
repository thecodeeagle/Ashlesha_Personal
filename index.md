---
layout: default
title: Aditya Wagh
---

<!-- Introduction -->
{% include intro.html %}

<!-- News -->
<div class="animate__animated animate__fadeIn">
    <h1 class="text-center">News</h1>
    <table class="rounded shadow border-0">
        {% for entry in site.data.news %}
        <tr>
            <td class="rounded ext-nowrap text-right"><b>{{entry.date}}</b></td>
            <td class="rounded text-left">{{entry.event}}</td>
        </tr>
        {% endfor %}
    </table>
</div>

<!-- Projects -->
{% include projects.html %}