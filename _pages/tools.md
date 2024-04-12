---
title: Get Involved
links:
  - link: /tools/MapSwipe/
  - link: /tools/tasking-manager/
---

There are two main ways to contribute map data for humanitarian purposes - MapSwipe and the Tasking Manager. Explore both of these tools below! :) 

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