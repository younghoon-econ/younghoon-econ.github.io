---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}

<style>
.teach {
  display: grid;
  grid-template-columns: max-content 1fr;
  column-gap: 1.5rem;
  row-gap: 0.35rem;
  align-items: baseline;
}
.teach .hdr {
  grid-column: 1 / -1;
  font-weight: bold;
  margin-top: 1.25rem;
}
.teach .hdr:first-child { margin-top: 0; }
.teach .yr {
  padding-left: 1.5rem;
  white-space: nowrap;
}
</style>

<div class="teach">
  <div class="hdr">National University of Singapore (Instructor)</div>
  <div class="yr">2026</div>
  <div>Financial Issues, Trade and Investment in Asia</div>
  <div class="yr">2025, 2026</div>
  <div>Introduction to Coding for Public Policy using Python</div>

  <div class="hdr">UCLA (Teaching Assistant)</div>
  <div class="yr">2021–2025</div>
  <div>Intermediate Microeconomic Theory</div>
  <div class="yr">2022</div>
  <div>Microeconomic Theory</div>
</div>
