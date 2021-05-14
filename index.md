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
<div class="animate__animated animate__fadeIn">
    <h1 class="text-center" id="projects">Projects</h1>
    <p class="text-justify">
        Below is a list of my notable projects. Some of them are academic projects,
        some are hobby ones. Feel free to have a look at whatever you find
        interesting!
    </p>
    <div class="col px-0">
        {% for project in site.data.projects %}
        <div class="row-md-6 row-lg-4 py-3">
            <div class="card rounded shadow p-4 alert-primary">
                <div class="row no-gutters">
                    <div class="col-md-4 mx-auto">
                        <img class="img rounded" src="{{project.image}}">
                    </div>
                    <div class="col-md-8 mx-auto">
                        <div class="card-body">
                            <h3 class="card-title text-capitalize my-0">{{project.title}}</h3>
                            <p class="card-text">{{project.description}}</p>
                            <a class="card-link btn btn-primary" href="{{project.docs}}">Docs</a>
                            <a class="card-link btn btn-success" href="{{project.code}}">Code</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        {% endfor %}
    </div>
</div>