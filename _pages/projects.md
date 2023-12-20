---
layout: page
title: projects
permalink: /projects/
#description: research in the lab
nav: true
nav_order: 2
display_categories: [ongoing research]
horizontal: true
---

<!-- pages/projects.md -->
<div class="projects">
<p> The ability to direct movement through the environment is crucial to animal fitness. Movement enables organisms to acquire food, avoid becoming food, and find and attract mates. The incredible range in animal size, evolutionary origin, and environmental pressures to do these things most optimally has led to a wide variety in locomotor design and performance range. Yet, most of these designs are built from a very similar set of of biological components. We are generally interested in the identity of mechanisms that allow(ed) this variation in design and performance to evolve in phylogenetically distinct species, but currently focus our work on mechanisms that control phenotypic plasticity in design and performance within single species. Interestingly, our work has demonstrated that at least one of these mechanisms is highly conserved across evolutionarily distant animal species.</p>
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_projects = site.projects | where: "category", category -%}
  {%- assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display projects without categories -->
  {%- assign sorted_projects = site.projects | sort: "importance" -%}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
<p> Current work in the lab aims to determine (1) mechanisms by which skeletal muscle responds to changes in body weight (e.g., loading, natural growth), energy availability and body temperature, and how environmental factors such as diet and infectious disease (2) interact with these mechanisms to determine locomotor phenotypes observed in nature, across an evolutionarily diverse set of animal species. Our work requires a multi-disciplinary approach, combining techniques from biomechanics and electrophysiology, behavioral ecology, ecological and molecular physiology, and broad sense functional genomics. Research projects in the lab and the animal models central to them therefore tend to vary in nature. As indicated earlier, most animals use skeletal muscles, and basic skeletal muscle structure and composition is highly conserved among animals. So, in order to derive general rules that govern how animals modify locomotor function in response to internal and external cues, we can and should study many animals that differ in locomotion type.</p>
</div>
