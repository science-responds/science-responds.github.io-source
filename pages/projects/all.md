---
title: All projects
permalink: /projects/all
---

# COVID-19 ML and Tech Related Open Science Projects

## Context

This document is a place to collect details on open science/open source technology based projects related to COVID-19. This includes modeling, public health interventions, medical technology, resource distribution, and more. Please feel free to add your own project or other projects that you know of! We just ask that you keep the doc organized and follow the yaml format below:

```yaml
title: Project Title
description: |
    A brief description of the project
resources:
  - "Links to important info about the project (include related articles if possible!)"
  - "For markdown yaml collision safety, use quotes"
needs: |
    What kind of folks can best contribute to this project?
involve: |
    Include links to sign up forms, GitHub issues, Slack channels, etc.
    Markdown accepted everywhere but the title.
tags:
  - ds
  - ml
```

Let’s make the most of our work from home time and try to help our fellow humans (and maybe learn some new skills!). 

To reach out to the doc creator, please email savannah.thais@gmail.com.

## Projects

| Name | Areas |
|------|-------|
{%  for project_pair in site.data.projects -%}
{%-   assign project-id = project_pair[0] -%}
{%-   assign project = project_pair[1] -%}
| [{{ project.title }}]({{ site.baseurl }}/projects/{{ project.tags[0] }}/#{{project-id}}) | {{ project.tags }} |
{% endfor %}


