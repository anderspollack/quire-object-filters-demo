---
epub: false
title: Objects Catalogue
layout: base.11ty.js
order: 101
# why does 'classes' need to be set?
classes:
  - objects-catalogue
---

# {{ title }}

This is the objects catalogue

{% renderTemplate "webc" %}
<objects-catalog filters="artist, medium" />
{% endrenderTemplate %}
