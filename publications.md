---
layout: default
title: Publications
---

## Journal Articles
{% bibliography --query @article %}

---

## Conference Papers
{% bibliography --query @inproceedings[!keywords~=workshop] %}

---

## Workshop Papers
{% bibliography --query keywords~=workshop %}
