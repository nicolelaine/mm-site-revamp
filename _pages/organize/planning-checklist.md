---
title: Planning Checklist

---

Here is a some planning checklists for you to use!

### Planning Checklist

<input type="checkbox"/> Download the <a href="https://drive.google.com/drive/folders/1gXkvuQNRhfyOVv6XjmncFFUIK4m_yCTb">complete Step-by-Step Guide to Hosting a Mapathon</a>. You can also download the <a href="https://drive.google.com/drive/folders/1y-PJ3MoHndFtm_Xcm_7qPMjtNYxbygCs">Missing Maps logo in common formats, as well as a customizable logo</a> to make one for your community!

<input type="checkbox"/> Recruit volunteers to help plan the event

<input type="checkbox"/> Book a space

<input type="checkbox"/> Register your event <a href="/events">here</a>

<input type="checkbox"/> Make banners or posters using the Missing Maps logo and/or the customizable community logo template

<input type="checkbox"/> Recruit participants using Eventbrite or another ticketing tool

<input type="checkbox"/> Pick a task using the Tasking Manager / or MapSwipe

<input type="checkbox"/> Ensure strong Wi-Fi

<input type="checkbox"/> If using the Tasking Manger, check that it passes your location's firewall

<input type="checkbox"/> Tables and chairs

<input type="checkbox"/> Projector & audio visual equipment

<input type="checkbox"/> Laptops for all participants (tablets are not compatible)

<input type="checkbox"/> Mice (if possible) for all participants

<input type="checkbox"/> Make sure you have contact info for your event spaces tech and support staff

<input type="checkbox"/> Extra extension cords

<input type="checkbox"/> Print materials

<input type="checkbox"/> Order snacks

<input type="checkbox"/> Prepare training materials

<input type="checkbox"/> Remind participants to create their OSM profile and download a browser that is not Internet Explore

<input type="checkbox"/> If hosting remote event, test platform including microphone and screenshare

<input type="checkbox"/> Extra extension cords

### Event Day Checklist

<input type="checkbox"/> Download a complete Step-by-Step Guide to Hosting a Mapathon from Training and Event Materials.

<input type="checkbox"/> Set up room

<input type="checkbox"/> Test wifi and Tasking Manager access on both pc and mac: note, the Tasking Manager is not compatible with Internet Explorer

<input type="checkbox"/> Tape extension cords to the floor for safety

<input type="checkbox"/> Set up registration table

<input type="checkbox"/> Put out printed resources

<input type="checkbox"/> Get presentations ready

<input type="checkbox"/> Set up snacks

<input type="checkbox"/> Have fun mapping!


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