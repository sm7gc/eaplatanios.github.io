---
layout: page
title: blog
nav: blog
permalink: /blog/
description: a simple platform for an ocassional brain dump
---

<div class="alert alert-danger" role="alert">
  This part of the site is still under construction.
</div>

<!-- <div id="blog" class="row mt-2 pt-3" style="overflow: visible !important;">
  {% assign sorted_posts = site.posts | sort: "importance" | reverse %}
  {% for post in sorted_posts %}
    <div class="project-card">
      {% if post.redirect %}
        <a href="{{ post.redirect }}" target="_blank">
      {% else %}
        <a href="{{ post.url | prepend: site.baseurl | prepend: site.url }}">
      {% endif %}
        <div class="card">
          <img class="card-img-top" src="{{ post.img | prepend: site.baseurl | prepend: site.url }}" alt="post thumbnail">
          <div class="card-body">
            <h5 class="card-title text-lowercase">{{ post.title }}</h5>
            <p class="card-text">{{ post.description }}</p>
          </div>
        </div>
      </a>
    </div>
  {% endfor %}
</div> -->
