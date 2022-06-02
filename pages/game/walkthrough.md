---
title: Making and Using Hypos, an Walkthrough
cat: game
permalink: game/hypo
---

This page digs into how to make and use hypos, efficiently and effectively.

[The first part emphasizes the importance of making hypos one **overlapping** rule at a time.](#part-1-making-hypos-with-overlap)

[The second part emphasizes the proper **re-use** of hypos.](#part-2-re-using-hypos)

The key takeaways are [here for part 1](#takeaways-for-making-hypos) and [here for part 2](#takeaways-for-re-using-hypos).

## Part 1: Making Hypos with Overlap

Suppose our game has 5 elements: t w x y z. 

And 2 rules:

1. w must be next to x
2. t goes before y 

Here's question 1:

> If t is in 3, what could be true?

{% capture summary %}
What's the first thing you do?
{% endcapture %}

{% capture details %}
Make a new number line and put t in 3, because this is [an IF question](questions.html#if).

> _ _ t _ _
{% endcapture %}
{% include details.html %}

{% capture summary %}
You need to follow all the rules, but which rule would be better to follow first?
{% endcapture %}

{% capture details %}
You'd be better off if you followed rule 2. 

Rule 2 overlaps with t, and you have t on the board. 

So you can add y in a cloud after t:

> _ _ t ( _ y )
{% endcapture %}
{% include details.html %}

{% capture summary %}
What's next?
{% endcapture %}

{% capture details %}
Now you can follow rule 1.

There's not enough space for (w x) after t, so they must go before, also in a cloud since they could go in either order.

> ( w x ) t ( _ y )
{% endcapture %}
{% include details.html %}

{% capture summary %}
Now you've taken care of all the rules. What could you do next?
{% endcapture %}

{% capture details %}
Ask yourself: Who's Left?

You've taken care of t w x and y. So z is the only leftover. There's only room after t, in the cloud with y. So you can add it there.

> ( w x ) t ( z y )
{% endcapture %}
{% include details.html %}

Now you've got every element on the board, and you took care of all the rules. You have a hypo! Or, technically, thanks to the clouds, you have 4 hypos.

### Takeaways for Making Hypos

1. Don't randomly follow rules. Follow the rule that *overlaps* with the elements you've already added to the board.
1. Don't make assumptions. Don't put an element somewhere just because it *could* go there. Use clouds to add what you know without committing to one possibility.
1. Notice what rules are taken care of. If you completely followed a rule or it can't be broken, then you don't need to worry about that rule for the rest of that hypo.
1. When you're out of rules, ask: Who's Left?

## Part 2: Re-Using Hypos

Reminder, we're playing a standard order game.

Elements: t w x y z

Rules: 

1. w must be next to x
2. t goes before y

Valid Hypo:

> ( w x ) t ( z y )

*Recall: (w x) is a cloud, which means w and x can switch positions. Same for (z y).*

Here's question 2:

> Which of the following must be true?
>
> (A) t is before z
>
> (B) t is not last.
>
> (C) w is before x
>
> (D) x is not first
>
> (E) y is before z

We can reuse the old hypo to disprove 3 of the answers for free.

{% capture summary %}
(A) t is before z
{% endcapture %}
{% capture details %}
In the hypo, t is before z. So (A) could be true. Whether it must *always* be true, we don't know.

Defer on (A).
{% endcapture %}
{% include details.html %}

{% capture summary %}
(B) t is not last.
{% endcapture %}
{% capture details %}
In the hypo, T is not last. That proves that (B) *could* be true.

Defer on (B) also. *But don't be discouraged!*
{% endcapture %}
{% include details.html %}

{% capture summary %}
(C) w is before x
{% endcapture %}
{% capture details %}
In the hypo, w could be before or after x. That proves that (C) *could be true* and that it *could be false*. Because it could be false, it doesn't need to be true. 

Eliminate (C).
{% endcapture %}
{% include details.html %}

{% capture summary %}
(D) x is not first
{% endcapture %}
{% capture details %}
In the hypo, x can go first. That proves (D) could be false.

Eliminate (D).
{% endcapture %}
{% include details.html %}

{% capture summary %}
(E) y is before z
{% endcapture %}
{% capture details %}
In the hypo, y can come after z. That proves (E) is not always true.

Eliminate (E).
{% endcapture %}
{% include details.html %}

What's left to do?

At this point, with 2 answers remaining, you might allow yourself a quick second to try to Wizard. That is: you can stare at the rules and at the remaining answers hoping that the right answer will magically appear. Because you've narrowed down the options, there's less to think about and it might be clear to you which answer is correct.

Don't spend more than 10 seconds Wizarding. When the magic doesn't happen, start making more hypos.

Since this is a *must be* question, we want to make hypos that disprove the wrong answers.

{% capture summary %}
What would disprove (A)?
{% endcapture %}
{% capture details %}
To disprove (A) show that t doesn't need to go before z. In other words, put t after z.

*Note: on test day, I actually say this (silently) to myself. I want to be sure of what I'm trying to do and why I'm trying to do it before I start making my hypo.*
{% endcapture %}
{% include details.html %}

{% capture summary %}
Where would you start the hypo to disprove (A)?
{% endcapture %}
{% capture details %}
Trick question: unlike the last hypo, there's no place you *must* start. 
{% endcapture %}
{% include details.html %}

{% capture summary %}
You could easily get hung up here. To help yourself keep moving: know your options.
{% endcapture %}
{% capture details %}
*Option 1:* Dive in. Put z somewhere before t. And remember that you started from a random place. If it breaks, consider making a new hypo with a different starting point OR go on to the next answer.

*Option 2:* Make a smart first move. A smart first move increases the chance that you'll be able to follow all the rules and make a valid hypo.

Try either, see if it works out. Then maybe try again, see what a different starting point leads to.
{% endcapture %}
{% include details.html %}

{% capture summary %}
Here's how I'd do it:
{% endcapture %}
{% capture details %}
step | reason
-- | --
z _ _ _ _ | put z first to take care of z -- t
z (w x) _ _ | take care of (w x) because it takes up space
z (w x) t y | take care of t -- y

Since I took care of all the rules, this is a valid hypo that disproves (A). 

I can select (B) with 100% confidence and move on.
{% endcapture %}
{% include details.html %}

### Reflection Questions

{% capture summary %}
Why is it OK to start at a random place while testing (A), but not for the IF question from before?
{% endcapture %}
{% capture details %}
On the IF question, we weren't testing an answer. If we started doing things randomly, we'd only end up with one possible way things could go after t was in 3. That might luckily point us to the right answer, or it might not.

When we're making a hypo to test an answer, we can more safely make arbitrary moves because we only need one hypo to work in order to disprove (or prove) that answer.
{% endcapture %}
{% include details.html %}

{% capture summary %}
Could we have reversed order and used the hypo from (A) on the IF question: "If T is in 3, what could be true?"?
{% endcapture %}
{% capture details %}
No. Unless the hypo meets the "IF" requirement, we can't reuse hypos on IF questions. In this case, that question asked about the specific situation in which T is in 3; and, in my hypo, T was in 4.

In contrast, we can (and did) reuse work from an IF question on a WHICH question. The WHICH questions ask about every possible situation, and that includes the limited situation of the IF question.

This is another reason to do IF questions before WHICH questions.
{% endcapture %}
{% include details.html %}

{% capture summary %}
What's the difference between "following" a rule, and "taking care of" a rule?
{% endcapture %}
{% capture details %}
We follow a rule when the rule forces us to put information into the board.

We take care of a rule when we:

1. Do something to make sure that rule can never be broken, or
2. Notice that it can never be broken.

(Following a rule is one way of taking care of that rule.)
{% endcapture %}
{% include details.html %}

### Takeaways for Re-Using Hypos

1. Reuse your hypos on future questions can get you free points, or at least free eliminations.
1. Know what you want to do before you start doing it.
1. Keep moving. When you get stuck, start making hypos. Use them to think through the problem on paper.
1. Do the IFs before the WHICHes.
1. "Taking care of" a rule is just as useful as "following" it.
