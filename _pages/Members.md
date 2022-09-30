---
layout: page
title: Lab group
permalink: /members/
description: List of current and past members of the group.
nav: true
nav_order: 1
display_categories: [Group Leader, current, alumni]
horizontal: true
---

<div class="projects">
    {%- if site.enable_members%}
      {%- for category in page.display_categories %}
        <h2 class="category">{{ category }}</h2>
          {%- assign categorized_members = site.members | where: "category", category -%}
          {%- assign sorted_members = categorized_members | sort: "pos" %}
          <!-- Generate cards for each member -->
          {% if page.horizontal -%}
          <div class="container">
            <div class="row row-cols-2">
              {%- for member in categorized_members -%}
                {% include members_horizontal.html %}
              {%- endfor %}
            </div>
          </div>
          {%- else -%}
          <div class="grid">
          {%- for member in categorized_members -%}
            {% include members.html %}
          {%- endfor %}
          </div>
      {%- endif -%}
      {% endfor %}
    {%- endif -%}
</div>
<!-- craeted members css (copied projects one)
also "enable_members" in config.yml -->
