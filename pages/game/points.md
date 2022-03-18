---
title: Get Points
cat: game
permalink: points.html
---

For each Logic Game, do the Qs in this order:

{% for item in site.data.LGRules -%}
1. [{{ item.name }}](#{{ item.name | slugify}})
{% endfor %}

At first, consult the instructions below as you play Games. Follow each of the steps carefully. 

Practice it right every time so that it becomes muscle memory. Later, you can start to add speed and even strategically skip steps.

*Beware: Every Advanced Move is also a potential time-suck.*

## How To Approach the 7 Types of LG Qs

{% for item in site.data.LGRules %}

### {{ item.name }} {#{{ item.name | slugify }}}

> {{ item.ex }}

{{ item.know }}

*Process:*

{{ item.process }}

*Advanced Move:* {{ item.adv }}

---

{% endfor %}

