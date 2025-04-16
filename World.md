---
title: The One Link
tags: [fabula-ultima, ttrpg/world, west-march]
created: 2025-03-23
modified: 2025-04-08
type: world
world: "[[ttrpgs/The One Link/World|The One Link]]"
campaign: "[[ttrpgs/The One Link/World|The One Link]]"
aliases: [The One Link]
cssclasses:
  - fabula-ultima
  - the-one-link
permalink: the-one-link
role: player
status: active
system:
  - "[[Fabula Ultima]]"
---

# The One Link

> Gaslamp Fantasy in a similar vein to FF6 or FF10, will feature dark elements in it with a world that might feel unforgiving, overall a story about overcoming obstacles and reaching others. Will have an asynchronous session 0 discussing tone, world building and rules.
>
> You wouldn't say that Humans are all bad to be honest, you might have a human friend, or be human yourself. However, this notion is becoming harder and harder to back as the Human majority empire of Darham has grown increasingly hostile towards its non human populous, and is on the way to conquer its neighboring state of Degorphia. However, you are not alone. A militant group opposing oppression and war called the One Link has emerged, and you have joined to protect those you hold dear and some that have yet to be.

> [!tldr|noicon shadow] House Rules
>
> - [West March Rules](https://docs.google.com/document/d/1CbdKeArKc3_T-TC_y72zGyYAYP5QDsimb0Ftvs2EVUk/edit?tab=t.0)
> - [Alterations to the Rules](https://docs.google.com/document/d/1yRW4vhBLeM8GDjDDnwcRBl-fb3nLf3Mnp__WNjkmyXY/edit?tab=t.0)

## Player Characters

```dataview
TABLE theme, class, identity, origin, race
FROM "ttrpgs/The One Link"
WHERE containsword(type, "pc")
SORT file.name ASC
```

![[one-link-players]]

## Sessions

```meta-bind-button
label: New Session
hidden: false
icon: "calendar-plus"
id: new-session-player
style: default
actions:
  - type: command
    command: quickadd:choice:69419a07-6a21-40ff-b309-812e65dee6bc
```

```dataview
TABLE gm, summary
FROM "ttrpgs/The One Link"
WHERE containsword(type, "session")
SORT sessionNum ASC
```

![[one-link-sessions]]

## Truths About the Campaign/World

> [!note|headless]
> Write down some facts about this campaign or the world that the characters find themselves in.

- [History of the World](https://docs.google.com/document/d/1GSPTL8M_FYgZdLS3CfCFIwitysFBTJeFlPUhsyHXGoY/edit?tab=t.0)
- [Nations & Settlements](https://docs.google.com/document/d/11fw-ocRIJEuAAhWIz9-jouGN9hgTjTp6cjgTdfjJL4U/edit?tab=t.0)

## Factions

```dataview
TABLE description
FROM "ttrpgs/The One Link"
WHERE containsword(type, "faction")
```

![[one-link-factions]]

## Prominent NPCs

- [[Peoples of the World]]
- [Peoples of the World | Google](https://docs.google.com/document/d/1NXiCMzjCcyKj83gMygSrUzHZgI5wyK54MwZ43EEIedc/edit?tab=t.0)
- [The World as it Grows | Google](https://docs.google.com/document/d/1_UfZemZc_Gj2kqQThuRDIMGVmNQUySM-R71PBD2Rpwc/edit?tab=t.0)

```dataview
TABLE pronouns, adjectives, faction, description
FROM "ttrpgs/The One Link"
WHERE contains(type, "npc")
```

![[one-link-people]]

## Nations

```dataview
TABLE description
FROM "ttrpgs/The One Link"
WHERE containsword(type, "place")
```

![[one-link-places]]
