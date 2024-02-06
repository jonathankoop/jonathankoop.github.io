---
title: Liquid test
---

<h1> {{ page.title }} </h1>

## Liquid let's you do a lot!

{{ page.title | upcase }}

{{ page.title | remove: "test" }}

{{ 'logo' | append: '.jpg' }}

{{ "Test test Test test." | truncatewords: 4 }}
