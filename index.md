---
title: Derechos civiles en Nuevo México
layout: base
date: 2026-09-16
---

# New Mexican Civil Rights in the 20th century

The twentieth century in New Mexico has seen tremendous advances in Civil Rights.  
New Mexico has evolved from a United States territory to one of the fifty states in the USA.

On this website, there are pages to explain some key civil rights movements during the century.

<!--Your name, photo, bio, and links come from `_data/nav-profile.yml`, not from this file. Edit them there and this block updates.-->
<!--To add a new card, create a new page and add those fields. To remove a card, delete `homepage: TRUE` from that page's front matter. To reorder cards, adjust the `position` values.-->


{% assign essays = site.pages | where: "homepage", true %}
{% include cards/card-stack.html cards = essays %}
