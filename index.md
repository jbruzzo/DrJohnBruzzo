---
layout: home
title: Home
---

# Bienvenido: Análisis de Fatiga con Python

Este blog es tu recurso completo para aprender **diseño y análisis de fatiga** utilizando herramientas open-source y Python.

## ¿Qué encontrarás aquí?

- **Tutoriales interactivos** con Jupyter notebooks
- **Guías paso-a-paso** para análisis de fatiga
- **Casos de estudio** con datos reales
- **Código reproducible** en Python (pyLife, py_fatigue)
- **Recursos** para ingenieros y estudiantes

## Últimos Artículos

{% for post in site.posts limit:5 %}
  <article>
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time>
    {{ post.excerpt }}
  </article>
{% endfor %}

---

**Nota:** Todos los tutoriales incluyen Jupyter notebooks descargables y código open-source.
