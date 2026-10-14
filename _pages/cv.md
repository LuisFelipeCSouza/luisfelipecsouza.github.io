---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Educação
* **Mestrado em Engenharia Elétrica** - Universidade Federal do Ceará (UFC), 2025-atual
* **Graduação em Engenharia Elétrica** - Universidade Federal do Ceará (UFC), 2020-2025

## Experiência
* **Mestrando** - GREI/UFC
  * Pesquisa em co-simulação de redes elétricas inteligentes

## Habilidades
* **Linguagens:** Python
* **Ferramentas:** OpenDSS

## Publicações
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

## Teaching
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
