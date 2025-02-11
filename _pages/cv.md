---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D in Civil Engineering**, *École nationale des ponts et chaussées*, 2024
* **Engineering diploma**, *École nationale des ponts et chaussées*, 2021
* **M.Sc. in Civil Engineering**, *University of Tokyo*, 2021

Work experience
======
* 2025-Current: **Postdoctoral Researcher**, *École nationale des ponts et chaussées*
  * Modelling the initial stress state in cement sheaths of deep wells
  * Well behaviour during cold CO<sub>2</sub> injection

* 2021-2024: **Doctoral Researcher**, *École nationale des ponts et chaussées*
  * Poromechanical modelling of cement-based materials
  * Development of a multi-physics simulation framework for 3D printing
  * Teaching in-situ geotechnical tests to master students

* Feb.-Jul. 2019: **Structural Engineer - Architect**, *bordas+peiro*
  * SHiFT building, *Issy-les-Moulineaux*: Heavy renovation of a 45000m2 office building with complex steel structures
  * Design of several ppst-tensioned concrete bridges up to 25m in a seismic area
  * API development in Revit to transfer geometries to and from Midas Gen for structural analysis

* Jul.-Dec. 2018: **Engineer - digital transition**, *Autoroutes Paris-Rhin-Rhône*
  * NumA project for the digitalisation of field jobs in highways
  * Introduction of digital project management

Skills
======
* Continuum mechanics
* Mechanics and physics of porous media
* Computational mechanics
  * Multi-physics material behaviour development with [MFront](https://thelfer.github.io/tfel/web/)
  * Finite Element Analysis using [FEniCSx](https://fenicsproject.org)
* Homogenisation

* Structural design

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


{% comment %}
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and leadership
======
* Currently signed in to 43 different slack teams
{% endcomment %}
