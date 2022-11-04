---
title: What's Your Job?
cat: reason
permalink: reason/job
---

This page describes the first step of approaching a Reasoning question: figuring out what the question is asking you to do.

Each question provides precise instructions, so you can always figure out what a question is asking on test day, but *thinking is expensive*.

Thankfully, the LSAT repeats itself, so you can anticipate what questions they're likely to ask you.
- *Most* of the questions in the Reasoning section will be one of the 12 common **types**, 
- *Every* question will fit into one of the 3 **families**, and 
- *Every* question will have one of 2 **styles**. 

By learning the tendencies of these common types, families, and styles, you can quickly and easily figure out how to approach every question in the Reasoning section.

{% capture summary %}
Note: Read the question before you look at the argument.
{% endcapture %}
{% capture details %}
There's some debate on whether reading the question first is a good idea. (As always, experiment with my suggestions and do what works best for you.)

The advantage of reading the question first is that it will help you properly focus your attention when you turn to the argument.

Reading the question first will be less useful if you do not memorize the common question families, styles, and types.
{% endcapture %}
{% include details.html %}

## Family

Broadly, a question will ask you to do one of 3 things to the argument:

1. **Describe** it, 
2. **Argue** with it, or 
3. **Infer** from it.

Every question fits into one of these 3 *families*. Recognizing a question's family tells you how to read the argument.

Family | Read For...
-- | --
[Describe][describe] | The structure of the argument
[Argue][argue] | The problem with the argument (but not the solution)
[Infer][infer] | Just the facts (there's no conclusion)

## Style

In addition to a family, every question also has one of two *styles*:

1. **Mechanical**, or
2. **Organic**

Style determines the type of ***attention*** you need to pay to the argument. 

Mechanical and Organic questions use different parts of your brain, which, if you don't know what's going on, can make the Reasoning section feel bewildering, exhausting, and even unfair.

Style | Type of Attention | Brain Hemisphere
-- | --
Mechanical | Pedantic. Robotic. <br>No new ideas. | Left
Organic | Holistic. Creative. <br>"What if"s are welcome. | Right

A question's style also determines the level of prediction you can make. [Learn how style shapes predictions.][predict]

## Type

There 12 common Reasoning question *types*. Each type inherits the general tendencies of its family and style, but knowing a question's specific type gives you more detailed instructions about what to look out for in the argument and answers.

{% capture summary %}
Caution: Learning too much about each question type can get in your way.
{% endcapture %}
{% capture details %}
If you try to learn all the nuances of every slightly different question type that's ever appeared on the LSAT, you'll waste precious time and energy on test day thinking about what you're *supposed* to be doing, instead of just doing it.

Simplify your knowledge by learning the more general patterns of the families and styles, rather than focusing on the types.

For example: 

    *Justify* type questions are in the *Argue* family and of *Mechanical* style. 

- Arguably, if you understand the tendencies of both the Argue family and the Mechanical style, you don't need to learn many specifics about the Justify type. 
- Conversely, by working through Justify questions, you can learn lessons that you can apply to other Argue family or Mechanical style questions.

Hone your knowledge by making mistakes -- learn what question families/styles/types you need a more structured approach on vs. what questions you can trust your intuitions on.
{% endcapture %}
{% include details.html %}

This table summarizes the 12 most common Reasoning question types:

Type | Family | Style | Basic Job
{% for item in site.data.LRType -%}
{% if item.family != "family" -%}
[{{item.type}}]({{item.family}}.html#{{item.type | slugify}}) | {{item.style}} | {{item.family}} | {{item.basics}}
{% endif -%}
{% endfor %}

The links in the table above provide more details about how to recognize and approach each of the common question types. Detailed descriptions of individual question are formatted using this structure:

{% assign whatfam = "family" %}
{% include ApproachLR.html %}

[describe]: describe.html
[argue]: argue.html
[infer]: infer.html
[specific]: predict.html#specific
[flex]: predict.html#flexible
[predict]: predict.html
