---
title: What's Your Job?
cat: reason
permalink: reason/job
---

## Every Question Gives You A Specific Task To Do

Read the question before you look at the Argument. Know what the Test is asking you to do before you try to do it.

The question always gives clear instructions. Still it is useful to know, in advance, what they're likely to ask you to do.

## Family

A Reasoning question can ask you to do one of 3 things with the Argument: Describe it, Argue with it, or Infer from it.

*All* Reasoning questions fit into one of these 3 Families:

1. [DESCRIBE][describe]
1. [ARGUE][argue]
1. [INFER][infer]

A question's Family tells you how you should try to Understand the Argument.

For an ARGUE question, you need to read critically, looking for problems so that you can HELP or HURT the Argument.

But you needn't argue with a DESCRIBE question.

And INFER questions don't even have complete Arguments, they merely offer some Facts. On INFER questions, the correct Answer *follows from* those Facts.

## Genus

In addition to a Family, *all* Reasoning questions have a Genus.

There are 2 Genera:

1. MECHANICAL
1. ORGANIC

A question's Genus tells you how to Predict.

On MECHANICAL questions, you should make [Specific Predictions][specific]. In contrast, ORGANIC questions tend to reward [Flexible Predictions][flex].

As a result, MECHANICAL questions reward very close, word-for-word readings. While ORGANIC questions benefit from a more holistic read.

## Species

Many questions also have a Species (aka a specific name). Each Species inherits the general task and tendencies of its Family and Genus.

Questions without a Species are defined well-enough by their Family and Genus. They do not require more specific classification.

Here's a chart of all the Species (that matter):

Family | Species | Genus
-- | -- | --
{% for item in site.data.LRSpecies -%}
{{ item.family | upcase }} | [{{ item.species }}]({{ item.family }}.html#{{ item.species | slugify }}) | {{ item.genus | upcase }}
{% endfor %} 

## Question Recognition Should Be Easy And Automatic, So Memorize Two Aspects Of Every Species

1. The keywords that indicate what Species it is.
1. It's Family, Genus, and your specific Job.

You don't have to use my words. Use words that make sense to you.

Make many flashcards for this, but remember, flashcards aren't a way to understand new ideas they're a way to lock-in what you already understand.

Keep it simple. Simplicity is a sign of understanding.

[Here's another cheat-sheet][cheat].

[describe]: describe.html
[argue]: argue.html
[infer]: infer.html
[specific]: predict.html#specific
[flex]: predict.html#flexible
[cheat]: https://docs.google.com/spreadsheets/d/1dxE_s49LAc6jxx_5zh-Av18kcTMO1BKtWPZGblT_vrQ/edit?usp=sharing
