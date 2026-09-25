---
title: Derechos civiles en Nuevo México
layout: base
date: 2026-09-16
---

# New Mexican Civil Rights

How is the term Civil Rights defined?  Through the stories presented on this website, several key New Mexican Chicanx figures will be presented, along with their tales and how they worked for equality and justice for all Chicanx people.

--Your name, photo, bio, and links come from `_data/nav-profile.yml`, not from this file. Edit them there and this block updates.

---


To add a new card, create a new page and add those fields. To remove a card, delete `homepage: TRUE` from that page's front matter. To reorder cards, adjust the `position` values.

{% assign essays = site.pages | where: "homepage", true %}
{% include cards/card-stack.html cards = essays %}
