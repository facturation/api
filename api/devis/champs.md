---
layout: default
nav_title: 'champs'
title: 'Liste des champs'
parent: 'Devis'
nav_order: 10000
---

{% include fields.md fields=site.data.fields.quote %}


## Ligne de facturation
{% include fields.md fields=site.data.fields.item %}