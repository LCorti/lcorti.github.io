---
title: "Supervision"
permalink: /supervision/
author_profile: true
---

{% include base_path %}

## 2025
<ul>
    {% for post in site.supervision reversed %}
        {% assign post_year = post.date | date: '%Y' %}
        {% if post_year == "2025" %}
            {% include archive-single-supervision.html %}
        {% endif %}
    {% endfor %}
</ul>

## 2024
<ul>
    {% for post in site.supervision reversed %}
        {% assign post_year = post.date | date: '%Y' %}
        {% if post_year == "2024" %}
            {% include archive-single-supervision.html %}
        {% endif %}
    {% endfor %}
</ul>

## 2023
<ul>
    {% for post in site.supervision reversed %}
        {% assign post_year = post.date | date: '%Y' %}
        {% if post_year == "2023" %}
            {% include archive-single-supervision.html %}
        {% endif %}
    {% endfor %}
</ul>

## 2022
<ul>
    {% for post in site.supervision reversed %}
        {% assign post_year = post.date | date: '%Y' %}
        {% if post_year == "2022" %}
            {% include archive-single-supervision.html %}
        {% endif %}
    {% endfor %}
</ul>
