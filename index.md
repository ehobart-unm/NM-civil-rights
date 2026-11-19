---
title: Derechos civiles en Nuevo México
layout: base
date: 2026-09-16
---

# New Mexican Civil Rights in the 20th century

<div class="story-box-row">

  <div class="story-box">

    <h3>During the twentieth century, the following events only happened in New Mexico:</h3>

    <ul>
      <li>In 1912, New Mexico became the 47th state in the union.</li>
      <li>In 1916, Pancho Villa invaded the United States at Columbus, New Mexico.</li>
      <li>In 1945, The first nuclear weapon in the world was tested.</li>
      <li>In 1947, An unidentified flying object (UFO) allegedly crashed at Roswell.</li>
      <li>In 1980, The Duran decree was signed.</li>
    </ul>

  </div>

  <div class="story-box">

    <p>
      This website was designed to provide the viewer with a look into
      some of the more seminal Civil Rights issues that impacted Chicanx
      (and in some cases all) residents of New Mexico.
    </p>

    <p>The site is broken into four components:</p>

<ul>
  <li>The Land Grant Movement</li>
  <li>Education &amp; Suffrage</li>
  <li>Prisoner Rights</li>
  <li>Environmental Justice</li>
</ul>

<p>
  The site is populated with the stories of some of New Mexico's
  most fierce advocates for Civil Rights, and focuses on the
  twentieth century.
</p>

</div>
</div>
<!--Your name, photo, bio, and links come from `_data/nav-profile.yml`, not from this file. Edit them there and this block updates.-->
<!--To add a new card, create a new page and add those fields. To remove a card, delete `homepage: TRUE` from that page's front matter. To reorder cards, adjust the `position` values.-->


{% assign essays = site.pages | where: "homepage", true %}
{% include cards/card-stack.html cards = essays %}
