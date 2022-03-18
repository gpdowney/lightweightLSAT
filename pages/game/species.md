---
title: The 7 Common Game Species
cat: game
permalink: species.html
---

[Here's a cheat-sheet][1].

## There are 2 Families of Logic Game

1. Order
2. Group

## Each Family contains 4 common Species

### Order

{% for item in site.data.LGSpecies -%}
{% if item.family == "Order" -%}
1. [{{ item.name }}](#{{ item.name }})
{% endif -%}
{% endfor %}

### Group

{% for item in site.data.LGSpecies -%}
{% if item.family == "Group" -%}
1. [{{ item.name }}](#{{ item.name }})
{% endif -%}
{% endfor %}
   
### Weirdos + Combos

In some Games, Elements are both Ordered and Grouped. Some Games are one-of-a-kind. 

Do not waste your time learning unusual and difficult Games until you're close to perfect on the common Games.

Learning the common Species will give you all the tools you need for the strange games.

## How to Recognize and Draw the Common Species

{% for item in site.data.LGSpecies %}

### {{ item.name }} {{ item.family }} {#{{ item.name}}}

*How you know:* {{ item.know }}

*Set-Up looks like:* {{ item.set-up }}

*Possible complications:* {{ item.complications }}

![{{ item.name }} Drawing](assets/images/species/{{ item.name }}.png)

---

{% endfor %}


[1]: https://docs.google.com/spreadsheets/d/1piQommFWLnj1z-3u4Abjs5gJvegD-fCMSs_bcZffbC4/edit?usp=sharing
