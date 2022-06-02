---
title: Don't Worry About Connections
cat: game
permalink: game/connect
---

## What Are Connections?

Connections happen either (a) when two rules can be combined into one, or (b) when a rule has secret implications.

For example, these two rules are connectable:

> A is next to B == (A B)
> 
> B is before C == B -- C

We could write them as one rule:

> (A B) -- C

And then we also know:

> C can't go first or second
> 
> A and B can't go last

Connections often happen when...
- the same element appears in multiple rules, or
- when elements are limited in where they can go.

## Not Connections

These two rules are not connectable:

> A is exactly one space away from B == (A_B)
>
> B is before C == B -- C

We could try to connect them like before:

> (A_B) -- C

But this drawing destroys important information, it wrongly makes it seem like C can't come in between A and B.

## Looking For Connections

You might see connections at any point while playing a game.

Other approaches to the games section emphasize seeing connections (or "inferences" as they often call them) upfront.

There are three risks for looking for connections upfront:

1. Looking for connections makes drawing difficult and slow.
1. Finding connections distracts you from the basic rules, which compromises the completeness and accuracy of your drawing.
1. Relying on connections in easy games makes it impossible to play hard games when you don't see the connections.

Connections are like magic. When it happens it's wonderful, but it can't be forced. Hence, those who look for connections are Wizards.

[Learn more about the pros and cons of being a Wizard here.][wiz]

Personally, I see connections more easily once I start playing the game. Once I start following the rules one by one, I notice that some of the rules tend to go together or that some limit the game more than others.

## Learning To See Connections

If you want to see connections more easily, you can try to bottle the magic with flashcards. After you see (or miss) a connection, make a flashcard that would help you recognize something similar next time.

Two examples, from above:

Side A | Side B
-- | --
What order rules love to connect? | solid clouds and relatives
Can these rules connect?<br><br> 1. A is next to B, and B is before C<br><br> 2. A is one space away from B, and B is before C | 1. Yes<br> *(A B) -- C* <br><br> 2. No

[wiz]: wizards.html
