---
layout: page
title: Blog
description: Notes and essays
permalink: /blog/
---

Here I document my experiments, thoughts, and analyses on a variety of topics.
This page also includes my study notes on books I read or courses I follow. I
hope my notebook helps you as much as it has helped me.

<ul>
  {% for post in site.categories.blog %}
    <li>
        <span>{{ post.date | date_to_string }}</span> » {% if post.highlight %}&starf; {% endif %}<a href="{{ post.url }}" title="{{ post.title }}">{{ post.title | truncate:72 }}</a>
    </li>
  {% endfor %}
</ul>
