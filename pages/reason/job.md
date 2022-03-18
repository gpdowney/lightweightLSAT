---
title: What's your JOB?
cat: reason
layout: default
permalink: job
---

## Every Q gives you a specific task to do

Read the Q before you look at the Argument. Know what the Test is asking you to do before you try to do it.

The Q always gives clear instructions. Still it is useful to know, in advance, what they're likely to ask you to do.

## Family

A LR Q can ask you to do one of 3 things with the Argument: Describe it, Argue with it, or Infer from it.

*All* LR Qs fit into one of these 3 Families:

1. [DESCRIBE](describe.html)
1. [ARGUE](argue.html)
1. [INFER](infer.html)

A Q's Family tells you how you should try to Understand the Argument.

For an ARGUE Q, you need to read critically, looking for problems so that you can HELP or HURT the Argument.

But you needn't argue with a DESCRIBE Q.

And INFER Qs don't even have complete Arguments, they merely offer some Facts. On INFER Qs, the correct Answer *follows from* those Facts.

## Genus

In addition to a Family, *all* LR Qs have a Genus.

There are 2 Genera:

1. MECHANICAL
1. ORGANIC

A Q's Genus tells you how to Predict.

On MECHANICAL Qs, you should make [Specific Predictions](predict.html#specific). In contrast, ORGANIC Qs tend to reward [Flexible Predictions](predict.html#flexible).

As a result, MECHANICAL Qs reward very close, word-for-word readings. While ORGANIC Qs benefit from a more holistic read.

## Species

Many Qs also have a Species (aka a specific name). Each Species inherits the general task and tendencies of its Family and Genus.

Qs without a Species are defined well-enough by their Family and Genus. They do not require more specific classification.

Here's a chart of all the Species (that matter):

<table>
    <caption>LR Qs by Family, Species, and Genus</caption>
    <tr>
        <th>Family</th>
        <th>Species</th>
        <th>Genus</th>
    </tr>
    {% for item in site.data.LRSpecies -%}
    <tr>
    <td>{{ item.family | upcase }}</td>
    <td><a href="{{ item.family }}.html#{{ item.species | slugify }}">{{ item.species }}</a></td>
    <td>{{ item.genus | upcase }}</td>
    </tr>
    {% endfor %} 
</table>

## Q recognition should be easy and automatic, so memorize two aspects of every Species

1. The keywords that indicate what Species it is.
1. It's Family, Genus, and your specific Job.

You don't have to use my words. Use words that make sense to you.

Make many flashcards for this, but remember, flashcards aren't a way to understand new ideas they're a way to lock-in what you already understand.

Keep it simple. Simplicity is a sign of understanding.

[Here's another cheat-sheet](https://docs.google.com/spreadsheets/d/1dxE_s49LAc6jxx_5zh-Av18kcTMO1BKtWPZGblT_vrQ/edit?usp=sharing).