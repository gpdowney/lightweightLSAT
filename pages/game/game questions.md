---
title: The Types of Game Questions
cat: game
permalink: game/questions
---

There are 3 major question types in the Games section:

Major Type | Basic Approach
-- | --
{% for item in site.data.GameQuestions -%}
{% if item.importance == "major" -%}
[{{ item.name }}](#{{ item.name | slugify }}) <br> *{{ item.ex }}* | {{ item.short }}
{% endif -%}
{% endfor %}

Do them in this order: LIST, IF, then WHICH.

*Knowing the major types is enough to get you through most games.*

When in doubt, any question can be approached as if it was a WHICH question. In other words, you can always test answers.

When you're ready to add complexity to your system, there are also 4 minor question types:

Minor Type | Basic Approach
-- | --
{% for item in site.data.GameQuestions -%}
{% if item.importance == "minor" -%}
[{{ item.name }}](#{{ item.name | slugify }}) <br> *{{ item.ex }}* | {{ item.short }}
{% endif -%}
{% endfor %}

Order matters less for these minor types. DOMINOS can be done earlier, while SUBSTITUTES should be skipped or saved for last.

More details on each type below...

***

{% for item in site.data.GameQuestions %}

### {{ item.name }} {#{{ item.name | slugify }}}

> {{ item.ex }}

{{ item.know }}

*Process:*

{{ item.process }}

*Advanced Move:* {{ item.adv }}

***

{% endfor %}

