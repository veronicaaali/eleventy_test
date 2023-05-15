---
title: 'Core 2: Interaction Lab'
layout: base.njk
---

## Veronica Li

### Project

  <div class="box-container">
  {% for project in collections.project %}
  <div><a href="{{ project.url }}">Project{{ project.data.index}}:<br>{{ project.data.title }}</a></div>
  {%- endfor %}
  </div>
  
### Assignment

  <div class="box-container">
  {% for assign in collections.assign %}
  <div><a href="{{ assign.url }}">{{ assign.data.title }}</a></div>
  {%- endfor %}
  </div>


