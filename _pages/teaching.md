---
title: "Teaching"
permalink: /teaching/
author_profile: true
---

## 2022

<ul>
  {% for post in site.teaching reversed %}
    {% assign post_year = post.date | date: '%Y' %}
    {% if post_year == "2022" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}
</ul>

## 2021

<ul>
  {% for post in site.teaching reversed %}
    {% assign post_year = post.date | date: '%Y' %}
    {% if post_year == "2021" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}
</ul>

## 2020

<ul>
  {% for post in site.teaching reversed %}
    {% assign post_year = post.date | date: '%Y' %}
    {% if post_year == "2020" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}
</ul>