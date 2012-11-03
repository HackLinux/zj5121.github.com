---
layout: page
title: FirefoxOS from Bottom to Top
---
{% include JB/setup %}

## Introduction
 I'm interested in the Andriod and new FirefoxOS(B2G) and want to understand how do they work.So I got a Pandaboard-ES board, and wish to experiment something for FirefoxOS by myself.

 In this blog, I will try to trace how a customized FirefoxOS for my Pandaboard-ES is constructed.


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



