---
title: Derechos civiles en Nuevo México
layout: base
date: 2026-09-16
---

# New Mexican Civil Rights in the 20th century

During the twentieth century, the following events only happened in New Mexico:
<LI>In 1912, New Mexico became the 47th state in the union</LI>
<LI>In 1945, The first nuclear weapon in the world was tested</LI>
<LI>In 1980, The Duran decree was signed (come up with something more exciting for this)</LI>

This website was designed to provide the viewer with a look into some of the more seminal Civil Rights issues that impacted Chicanx (and in some cases all) residents of New Mexico.

The site is broken into four components:
<LI>The Land Grant Movement</LI>
<LI>Education & Suffrage</LI>
<LI>Prisoner Rights</LI>
<LI>Environmental Justice</LI>

The site is populated with the stories of some of New Mexico's most fierce advocates for Civil Rights, and focuses on the twentieth century

<!--Your name, photo, bio, and links come from `_data/nav-profile.yml`, not from this file. Edit them there and this block updates.-->
<!--To add a new card, create a new page and add those fields. To remove a card, delete `homepage: TRUE` from that page's front matter. To reorder cards, adjust the `position` values.-->


{% assign essays = site.pages | where: "homepage", true %}
{% include cards/card-stack.html cards = essays %}
