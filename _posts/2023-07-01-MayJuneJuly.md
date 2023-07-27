---
layout: post
title: "May, June, and July - Early Summer in Minetest (14)"
contributors:
  - MisterE
  - Rubenwardy
  - EmptyStar
  - Athozus
  - Lemente
  - CodeScratcher
  - GreenXenith
description: >
  Work on the 5.8 release continues with some exciting new engine improvements. An
  old classic game makes its way onto Content Database, and Lemente shares about
  the use of Minetest in education.
#forum_topic: https://forum.minetest.net/viewtopic.php?f=18&t=29501
tags:
  - last_month
image: /static/blog/2023_MayJune/header.png
asuna:
- src: /static/blog/2023_MayJune/asuna1.png
  caption: Crystal Forest
- src: /static/blog/2023_MayJune/asuna2.png
  caption: Cursed Lands Under
---

Work on the 5.8 release continues with some exciting new engine improvements. An
old classic game makes its way onto Content Database, and Lemente shares about
the use of Minetest in education.

<!-- more -->

- [Engine News](#engine-news)
- [Games News](#games-news)
- [Mods News](#mods-news)
- [Art and Builds](#art-and-builds)
- [Education](#education)
- [In Other News](#in-other-news)
- [Server News](#server-news)
- [In Other News](#in-other-news)

## Engine News

Several improvements have been in the works for the 5.8 release. For
touchscreens, it will be possible to place nodes with a single tap. New texture
modifiers were added, allowing modders to adjust or colorize textures using hue,
saturation and lightness, adjust contrast, create textures of arbitrary size,
and more.

A really important step towards a better user interface was taken, with
Rubenwardy's settings page redesign being merged.

{% include figure.html src="/static/blog/2023_MayJune/settings.png" caption="The new settings menu" %}

Another major improvment is Desour's sound refactor which fixes several bugs,
including loading large sound files causing lag, and also adds new features such
as fade-in for positional audio.

Finally, x2048 added antialiasing post-processing filters for smoother graphics.

## Games News

### Asuna

{% include figure_gallery.html items=page.asuna %}

[Asuna](https://content.minetest.net/packages/EmptyStar/asuna/) by
[EmptyStar](https://content.minetest.net/users/EmptyStar/) welcomes the
otherworldly wonders of the
[Everness](https://content.minetest.net/packages/SaKeL/everness/) mod to its
domain! From the sparkling vistas of the crystal forests to the haunted bogs of
the cursed lands, down to the depths of its lush caves, icy caverns, and beyond—
Everness is now a crown jewel of the Asuna experience. With a few personal
touches and careful integration into Asuna's fantastic fabric of biomes,
Everness graces every corner of the world.

Along with the inclusion of Everness, much work has been done to improve
Asuna's underground, new biomes have been added, and landscapes are now more
diverse than ever. Join the new [Asuna Discord
server](https://discord.gg/DqtD9kuk2R) to stay up-to-date with Asuna's
development.

### BlockColor

{% include figure.html src="/static/blog/2023_MayJune/blockcolor.png" caption="Blocks and colors" %}

In an effort to preserve an old, interesting game project, the
[mt-historical](https://github.com/mt-historical) organization has added
[BlockColor by
MrChiantos](https://content.minetest.net/packages/mt-mods/blockcolor/) to
ContentDB. The name says it all: It's a world of blocks painted with a soothing
palette of colors.

### Mineclone 2

The latest [Mineclone](https://content.minetest.net/packages/Wuzzy/mineclone2/) update, titled "The Very Nice Release", went live last
month. It was mostly a quality-of-life update, with bugfixes, performance,
texture and sound improvements.

{% include youtube.html id="5aHym2jUB1M" %}

## Mods News

### Mail

{% include figure.html src="/static/blog/2023_MayJune/mailmod.png" caption="New Mail Features" %}

Many servers rely on the [Mail
mod](https://content.minetest.net/packages/mt-mods/mail/) for in-game
communication. Since the beginning of the year, the
[mt-mods](https://github.com/mt-mods) organization has developed many new
features and fixed several bugs using feedback from the [YourLand
server](https://your-land.de/). They also added translations for at least 6 new
languages. The biggest new addition is the "Sent Messages" folder, which
required a complete rewrite of the storage system (thanks to BuckarooBanzay).

Other new features include mailing lists, sorters and filters, drafts,
multiple-message selection, and a new "About" page.

Most recently, the [1.2.0
release](https://github.com/mt-mods/mail/releases/tag/1.2.0) has brought
settings, a trash system, major performance improvements, and bug fixes.

Contributors to the mail mod include S-S-X, BuckarooBanzay, fluxionary, and the
YourLand server.

### Plushie Invasion

{% include figure.html src="/static/blog/2023_MayJune/plushies.png" caption="Fluffy" %}

You may have noticed the recent uptick in plushies in Minetest. Three mods -
[Fumo Plushies](https://content.minetest.net/packages/aSliceOfCake/fumoplushies/), and [Amogus Plushie](https://content.minetest.net/packages/aSliceOfCake/amogus/) by [aSliceOfCake](https://content.minetest.net/users/aSliceOfCake/), and [Plushies](https://content.minetest.net/packages/Atlante/cat_plushies/) by [Atlante](https://content.minetest.net/users/Atlante/) have
greatly increased the availablility of fluffy decorations.

### Nodecore Cat Realm

{% include figure.html src="/static/blog/2023_MayJune/nc_catrealm.jpg" caption="Cat Kingdom" %}

The [Nodecore CatRealm modpack](https://content.minetest.net/packages/Warr1024/catrealm/) by [Warr1024](https://content.minetest.net/users/Warr1024/) and Mearson introduces a new dimension
inhabited by cats. Craft a portal, pay a cat prill, and step out onto the
mythical cat sky islands. Find new ores, and craft powerful tools. Conquer the
land of the cats!

### Arena_lib

{% include figure.html src="/static/blog/2023_MayJune/weather.png" caption="Rain in the Arena" %}

Development on [Arena_lib](https://content.minetest.net/packages/Zughy/arena_lib/) by [Zughy](https://content.minetest.net/users/Zughy/) is nearing completion. With the latest update
(6.3.0, "Piove?") you can choose from 3 weather effects to stylize your minigame
arena: rain, snow, or dust. You can also change the saturation of the screen in
the minigame, which allows for a black-and-white effect or to just tone down the
colors a bit.

## Art and Builds

{% include figure.html src="/static/blog/2023_MayJune/bamboocave.png" caption="Bamboo Cave With Pool, shot by Heather" %}

{% include figure.html src="/static/blog/2023_MayJune/carved_land.png" caption="Carved Landscape, shot by Lemente" %}

## Education

### Minestory

{% include figure.html src="/static/blog/2023_MayJune/minestory.png"
    caption="Students recreating the Lascaux cave in Minetest during Minestory"
    %}

Every year, hundreds of students from schools across France participate in
[Minestory](http://minetest.wp.ac-dijon.fr/minestory-frise-immersive-de-sites-du-patrimoine-architectural/),
an event created by French teacher Julien Crémoux in 2019. Students are tasked
to replicate a heritage site from their local area such as Notre-Dame or the
Louvre castle on a Minetest server, and then give a virtual tour of their
creation. The event is also an opportunity for students to provide feedback and
ideas regarding educational projects.

This year's Minestory event was hosted in Terrasson-Lavilledieu in France on May
31st, 2023. 150 of the 413 participants visited the nearby [Lascaux
cave](https://en.wikipedia.org/wiki/Lascaux), which is known for its prehistoric
cave paintings. The next day, Thomate, Riwad, and Lemente organised a 10-minute
workshop (one of 14 other workshops) in which students decorated a Minetest cave
with simple cave paintings using the
[ggraffiti](https://content.minetest.net/packages/grorp/ggraffiti/) and
[cave_painting](https://github.com/Lemente/cave_painting) mods. The students
were challenged to draw one of the animals they saw depicted the previous day.

## Server News

### Open Survival
<sub>minetest.skiscratcher.com:30000</sub>

{% include figure.html src="/static/blog/2023_MayJune/opensurvival.png"
    caption="A Fresh Start" %}

On June 14, 2023, Open Survival had a total reset. To remedy increasing
management complexity and provide a new experience for long-time players, the
Open Survival team removed several mods and completely reset the world and the
players.

## In Other News

Better late than never, right?