---
layout: default
title: Aditya Wagh
---

<!-- Introduction -->
{% include intro.html %}

<!-- News -->
<div class="animate__animated animate__fadeIn">
    <h1 class="text-center">News</h1>
    <table class="border-none">
        {% for entry in site.data.news %}
        <tr class="border-none">
            <td class="text-nowrap text-right py-1"><b>{{entry.date}}</b></td>
            <td class="py-1 text-left">{{entry.event}}</td>
        </tr>
        {% endfor %}
    </table>
</div>

<!-- Projects -->
{% include projects.html %}