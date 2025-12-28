---
title: MY FIRST NOTE
date: 2024-01-15
feed: show
image: /images/npcs/test-npc.jpg
pronouns: he/him
species: Human
role: Guild Liaison
faction: Green Door Solutions
location: Arcadia – The Warren
tags:
  - npc
  - arcadia
  - guild
---

<!-- Infobox include -->
{% include infobox.html
   title=page.title
   image=page.image
   pronouns=page.pronouns
   species=page.species
   role=page.role
   faction=page.faction
   location=page.location
   tags=page.tags %}

## Overview

This is **normal markdown content** and will wrap naturally on the left side of the infobox,
exactly like a wiki article.

You can freely use:
- **Wiki links**: `[[Green Door Solutions]]`
- Regular markdown
- Headings, lists, tables, etc.

## Background

More content here.  
On mobile, the infobox will automatically stack above the text.

<div style="clear: both;"></div>

## Notes

Optional section for extra details.
