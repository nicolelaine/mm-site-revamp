---
title: Get Involved
links:
  - link: /tools/MapSwipe/
  - link: /tools/tasking-manager/
  - link: /tools/validation/
  - link: /tools/field-mapping/


---

There are lots of way to contribute map data for humanitarian purposes - explore below and have fun!

{::nomarkdown}
{% assign subitems="" | split: ',' -%}
{% for link in page.links %}
  {% assign item=site.pages | find: "url", link.link %}
  {%- if item -%}
    {%- assign subitems=subitems | push: item -%}
  {%- endif %}
{% endfor %}
{% include item_list.html items=subitems %}
{:/nomarkdown}