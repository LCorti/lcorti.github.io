---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% if site.author.googlescholar %}
  You can also find the updated list of articles on <a href="{{site.author.googlescholar}}" target=_blank>my Google Scholar profile</a> (opens in another page).
{% endif %}

## 2025
---
<ul>
  {% for post in site.publications reversed %}
    {% assign post_year = post.date | date: '%Y' %}
    {% if post_year == "2025" %}
        {% include archive-single-publication.html %}
    {% endif %}
  {% endfor %}
</ul>

## 2024
---
<ul>
  {% for post in site.publications reversed %}
    {% assign post_year = post.date | date: '%Y' %}
    {% if post_year == "2024" %}
        {% include archive-single-publication.html %}
    {% endif %}
  {% endfor %}
</ul>

## 2023
---
<ul>
  {% for post in site.publications reversed %}
    {% assign post_year = post.date | date: '%Y' %}
    {% if post_year == "2023" %}
        {% include archive-single-publication.html %}
    {% endif %}
  {% endfor %}
</ul>

## 2022
---
<ul>
  {% for post in site.publications reversed %}
    {% assign post_year = post.date | date: '%Y' %}
    {% if post_year == "2022" %}
        {% include archive-single-publication.html %}
    {% endif %}
  {% endfor %}
</ul>

## 2021
---
<ul>
  {% for post in site.publications reversed %}
    {% assign post_year = post.date | date: '%Y' %}
    {% if post_year == "2021" %}
        {% include archive-single-publication.html %}
    {% endif %}
  {% endfor %}
</ul>
