---
title: The Common Game Types
cat: game
permalink: game/types
---

## Fundamentally, There Are Only 2 Families Of Games

1. Order
2. Group

### Each Family Contains 4 Common Types

Type | How To Recognize
-- | --
***Order*** | **one element at a**
[Standard](#Standard) | no funny business
[Unequal](#Unequal) | too many elements or too many spots
[Flow](#Flow) | every rule is a relationship
[Multi](#Multi) | element + extra variable
***Group*** | **many elements go with / into each group**
[Fixed](#Fixed) | groups of fixed size
[Flexi](#Flexi) | groups of changing or unknown size
[Binary](#Binary) | exactly 2 groups + every rule is a conditional
[Grid](#Grid) | base + element + extra variable

### Weirdos And Combos

The above list is intentionally incomplete.

In some games, elements are both ordered and grouped. Some order games aren't ordered. Some group games are ordered. Some games are one-of-a-kind. 

Do not waste your time learning how to approach unusual games until you're close to perfect on the 8 common types.

Learning the common types will give you general purpose tools that you can use on the unusual games. And knowing what's normal will help you see more clearly what's unusual.

Conversely, knowing all the nuances of how to handle the hard cases risks complicating your approach to easier games. And learning the unusual games gives you specific tools that only help on a rare type of game.

## How To Recognize And Draw The Common Types

{% for item in site.data.LGSpecies %}

### {{ item.name }} {{ item.family }} {#{{ item.name}}}

*How you know:* {{ item.know }}

*Set-Up looks like:* {{ item.set-up }}

*Possible complications:* {{ item.complications }}

![{{ item.name }} Drawing](../assets/images/species/{{ item.name }}.png)

***

{% endfor %}

[1]: https://docs.google.com/spreadsheets/d/1piQommFWLnj1z-3u4Abjs5gJvegD-fCMSs_bcZffbC4/edit?usp=sharing
