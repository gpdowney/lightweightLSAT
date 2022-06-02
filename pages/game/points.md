---
title: Prove And Disprove Answers
cat: game
permalink: game/points
---

Once you've drawn the game, you can start play the game. As much as drawing was about knowledge, playing is about skill.

**The key skill of playing games is proving and disproving the answers. The best way to (dis)prove answers is by robotically making and using hypos.**

By default, most human brains don't like thinking this way. At first, making hypos will feel laborious, and using hypos will feel unnatural. But with deliberate practice, you can learn to make and use hypos smoothly.

[How to practice skills, generally][skill].

The rest of this page teaches how to:

1. [Efficiently make hypos](#making-hypos-efficiently)
    - [Generate hypos for the major question types](#how-you-generate-hypos-depends-on-the-question-type)
    - [Be smooth](#be-smooth)
2. [Effectively use hypos](#using-hypos-effectively)
    - [Know what you're looking for](#know-what-youre-looking-for)
    - [Reuse hypos](#reuse-hypos)
3. [Practice these skills](#skill-practice-ideas)

Or you might prefer to learn these ideas by [reading this more detailed example.][walkthru]

## Making Hypos Efficiently

A hypo is an arrangement of every element on the board.

A valid hypo follows all of the rules, or at least doesn't break any rule.

### How You Generate Hypos Depends On The Question Type

There are three major types of questions:

Question | What it's Asking
-- | --
{% for item in site.data.GameQuestions -%}
{% if item.importance == "major" -%}
{{ item.name }} <br> *{{ item.ex }}* | {{ item.ask }}
{% endif -%}
{% endfor %}

[Learn more about how to approach these major questions, as well as the 4 minor types, here.][questions]

Doing the questions in that order (LIST and IF before WHICH) will help you make hypos more easily.

1. The LIST question gives you a free hypo.
2. IF questions give you a starting point for a new hypo. You add the new information (X into 3) to a new board, and then follow the rules to create one (or more) hypos.
3. You may need to make more hypos to directly test the answers on WHICH questions.

### Be Smooth

The key to efficiency isn't rushing, but smoothness.

Write your hypos down. Drawing your hypos will help you be methodical, and you can potentially reuse them.

Go one rule at a time. Or better yet, go one **overlapping** rule at a time.

> For example, after you put X to spot 3, look first at any rules that include element X or spot 3.

When you've exhausted the rules, ask: **"Who's left?"**

Often the answer will be the elements not attached to any rules, aka the **leftover** elements. Get these leftovers into your hypo. When you make sure all the elements have a place, you'll make your hypo more readable and useful.

{% capture summary %}
Advanced move... Keep your hypos flexible.
{% endcapture %}
{% capture details %}
When you add the leftovers to you hypo, don't just add them to one spot. Put them in a cloud over the board. Or use slashes, arrows, or some other symbol to show that they could go in multiple spots.

That way your one hypo will actually be several hypos, which will make it more useful on future questions.
{% endcapture %}
{% include details.html %}

## Using Hypos Effectively

Hypos are powerful, but their power is limited. A hypo is just one possibility; it can't show you what must be, it can only show you what could be.

That means hypos can:

1. **prove** the 1 correct answer on *could be* questions, and
2. **disprove** the 4 incorrect answers on *must be* questions.

Adding in the concepts of *true* and *false* makes things a little trickier.

### Here's One Way To Think About It

Could be True | the answer is **right** if it happened, even just one time, in any hypo
Could be False | the answer is **right** if it *didn't happen* in any hypo
Must be True | the answer is **wrong** if it *didn't happen* in any hypo
Must be False | the answer is **wrong** if it happened in any hypo

### Here's An Example To Help You Think Through It

Suppose we knew this was a valid hypo:

> Shirt 1: red and blue
>
> Shirt 2: red and yellow

And we have these statements to evaluate:

> A. Both shirts contains yellow.
> 
> B. Both shirts contain red.

{% capture summary %}
What do we know about these statements, based on our single hypo?
{% endcapture %}

{% capture details %}
&nbsp; | Could it be True | Could it be False | Must it be True | Must it be False
-- | --
A | ? | Yes | No | ?
B | Yes | ? | ? | No
{% endcapture %}
{% include details.html %}

{% capture summary %}
Assuming A and B are the only two answers, how should we approach each type of question? 
{% endcapture %}
{% capture details %}
Could be True | Defer on A, then select B (and move on)
Could be False | Select A (and move on, don't need to read B)
Must be True | Eliminate A, then select B (because B is the only remaining answer).
Must be False | Defer on A, then eliminate B, then select A (because A is the only remaining answer).
{% endcapture %}
{% include details.html %}

### Here's A More Visual Way To Think About It

![diagram of could vs must / true vs false][1]

### Know What You're Looking For

Could, false, must, true, it can all get a little bewildering. 

Before you look to your hypos to (dis)prove an answer, know what you're looking for.

And don't be afraid to stop to remind yourself what you're doing.

This will become more automatic with deliberate practice, but make sure you practice it slowly at first so that you can get it right.

### Reuse Hypos

Within a game, you can get many uses from a single hypo.

Reusing hypos is one of the best ways to save time. 

{% capture summary %}
Caution: avoid revising hypos
{% endcapture %}
{% capture details %}
You might be tempted to quickly switch two elements in your hypo to make it useful on a future question.

This switching is dangerous. When you make the switch, you might accidentally break a rule.

Instead, when you make your hypos make them flexible, using clouds or arrows or slashes.

If you do revise a hypo, quickly check all the rules to make sure you didn't break anything.
{% endcapture %}
{% include details.html %}

## Skill Practice Ideas

- Name the type of all the question in a section.
- Skip the draw step, just get into the questions and make hypos.
- Make as many hypos as possible. Prove and disprove every answer two different ways.
- Make as few hypos as possible. Get maximal re-use out of each hypo you make.
- Put "Overlap" on a sticky note while you make hypos.
- Put "Who's Left" on a sticky note while you make hypos.
- Tell yourself (or write down) what you want to (dis)prove on each question and each answer.

[1]: ../assets/images/couldmust.png
[questions]: questions.html
[swans]: swan.html
[skill]: ../fundamentals/practice.html#skill-work
[walkthru]: hypo.html
