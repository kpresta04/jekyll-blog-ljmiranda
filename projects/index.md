---
layout: page
title: Projects
description: Projects of Lester James V. Miranda
permalink: /projects/
---

Here are some of the works that I've done from my side-projects and 
course requirements. These projects revolve around the topics of machine
learning and data science, so I hope you enjoy reading through them!

<ul>
    {% for post in site.categories.projects %}
    <li>
        <span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
    </li>
    {% endfor %}
</ul>