# the Reasoning Section

In the Reasoning section, each question is about a short argument.

To answer each question, you'll do 5 basic steps:

1. [Know Your Job](#step-1-know-your-job)
1. [Understand the Argument](#step-2-understand-the-argument)
1. [Pause to Predict](#step-3-pause-to-predict)
1. [Eliminate, Defer, or Select each Answer](#step-4-eliminate-defer-or-select)
1. [Move On or Revise](#step-5-move-on-or-revise)

Here's an example of what that looks like:

[![example of a Reasoning question][1]][1]

This page provides an overview of each step, with some ideas for practice and links to further reading.

## Step 1: Know Your Job

Read the question first. (That's the part that ends in a "?"). The question gives you a job to do. And it's useful to know what your job is, before you start doing it.

Every question fits into one of 3 **families**. Most questions also have a specific **type**. The family tells you generally how to read the argument. The type provides more specifics about what you can expect from the argument and answers.

{% capture summary %}
Practice Tip: Memorize the families and types.
{% endcapture %}
{% capture details %}
Save time and energy on test day by memorizing how to (1) recognize and (2) approach each family and type.
{% endcapture %}
{% include details.html %}

### Question Family

Questions fall into 3 **families**. Questions will ask you to either:

1. **Describe** the argument
2. **Argue** with the argument, or
3. **Infer** from the argument.

Recognizing a question's family helps you know what to expect from the argument.
    
    For example, when you're in the *Argue* family, you can be confident that the argument has at least one problem. Your job is to find that problem.

[Learn more about each of the question families.][family]

### Question Type

Most Reasoning questions also have a **type**. There are 12 common types:

Question Type | Family
-- | --
{% for item in site.data.LRType -%}
[{{item.type}}](reason/{{item.family}}.html#{{item.type | slugify}}) | {{item.family}}
{% endfor %}

Recognizing the question's type gives you a specific task.
    
    For example, on *Conclusion* questions, the correct answer will paraphrase the argument's conclusion. So your job is to find the argument's conclusion and then figure out which answer means the same thing.

{% capture summary %}
Caution: Every question has a family, but some questions lack a type.
{% endcapture %}
{% capture details %}
Other guides attempt to give you a complete list of every possible question type. And they give you much more to memorize about each question type.

Instead, I offer the families to simplify your learning. Knowing each family's general tendencies helps simplify in two ways:

1. By memorizing the family's shared patterns, you don't have to re-memorize that information for each type within the family.
2. Instead of memorizing all the unusual question types, you can use the general approach for the family.

If you think a question type repeats often enough to be worth the brain space, go ahead and memorize it.
{% endcapture %}
{% include details.html %}

## Step 2: Understand the Argument

Every argument on the LSAT has two essential parts:

- one or more **facts**, which are the basis of the argument; and
- the **conclusion**, which is the point of the argument.

{% capture summary %}
Exception: Infer family questions only give you facts.
{% endcapture %}
{% capture details %}
In the Infer family, the "argument" will not have a conclusion. It will give you a series of facts, and your job is to find the allowable conclusion.

[Learn about the Infer family.](reason/infer.html)
{% endcapture %}
{% include details.html %}

To understand the argument, you will need to...

1. **Break down** the argument into facts and conclusion, and then 
2. **Boil down** the argument to its essential meaning.

### Break it Down

In contrast to how you argue in real life, on the LSAT you must *accept that the facts are true*. Instead of fighting the facts, you argue by showing that the facts do not support the conclusion. 

[Learn how to argue without fighting the facts.][validity]

Breaking down the argument's structure clarifies what you must accept (the facts) and what you can challenge (the connection between the facts and conclusion).

{% capture summary %}
Practice Tip: Memorize the fact and conclusion words.
{% endcapture %}
{% capture details %}
Fact and conclusion words are the easiest way to distinguish fact from conclusion.

The fact words are the most reliable and least noticed, so noticing them will give you an edge. 

The 4 most common fact words are:
- For
- After all
- Because
- Since
{% endcapture %}
{% include details.html %}

[Learn how to break down arguments.][break]

### Boil it Down

The second step of understanding is to boil the argument down to its essential meaning.

LSAT arguments are often poorly written. When you boil it down, you attempt to translate and simplify the argument without changing the meaning.

{% capture summary %}
Practice Tip: Find the verb.
{% endcapture %}
{% capture details %}
Bad writing often obscures verbs.

You can untangle many a confusing sentence by finding the hidden verb. 

[Learn how verbs hide.](/reason/verbs.html)
{% endcapture %}
{% include details.html %}

[Learn how to boil down arguments.][boil]

## Step 3: Pause to Predict

After reading the argument and before looking at the answers, pause to attempt to predict the answer.

[Learn how to predict][predict]

Predicting does not usually mean guessing the exact *words* that will appear in the argument. Rather, predicting is an opportunity to check and reinforce your *understanding* of the argument so that you don't get turned around by the answers.

### Levels of Prediction

There are three levels of prediction you can make:

**Anchor** prediction | grounds you in your understanding
**Flexible** prediction | identifies the argument's problem <br>(but not its solution)
**Specific** prediction | exactly anticipates the correct answer

### Question Style

The level of prediction you aim for depends on the question's **style**. 

There are 2 styles:

Style | How to Read | Type of Prediction
**Mechanical** | *robotically:* <br>pay pedantic attention to each part of the argument | Specific
**Organic** | *creatively:* <br>pay holistic attention to the whole argument | Flexible

### Always Predict

When all else fails on a hard question, or you want to save time on an easy question, you should still pause for a second to make an Anchor prediction.

Making a prediction is the best way to defeat the LSAT's most devious trick: confusing answer choices.

[More on how the answers are designed to confuse you.](resources/confuse.html)

{% capture summary %}
Practice Tip: Write down your predictions.
{% endcapture %}
{% capture details %}
When you practice writing down your predictions you force yourself to make predicting into a habit. Although by test day you'll want to predict in your head.

Writing down your predictions also helps improve your review. When you review a written prediction, you can more honestly compare that prediction to both the correct answer and the argument. 

- When your prediction was way off, you can look back to the argument to see if there were any important clues you missed. Then you can make a flashcard that will help you notice similar clues in similar situations.
- Or your prediction might have been pretty close. That teaches you that you should trust yourself more and not let the answers control your thinking.
{% endcapture %}
{% include details.html %}

## Step 4: Eliminate, Defer, or Select

Once you have a prediction, you're ready for the answers.

On the digital LSAT, you can do one of 3 (useful) things to any given answer:

Option | When the answer is... | What to click
-- | -- | --
**Eliminate** | Poisoned, aka you know why it's bad | The button on the right side to cross it out.
**Defer** | Weird, aka you aren't sure | Nothing.
**Select** | The least bad one left, or you love it | The button on the left side, which should turn green.

There are also two non-useful things you can do:
1. *Waffling* back and forth between answers without deciding; and
2. Endlessly *staring* at the answers. 

Waffling and staring are the two greatest wastes of time on the LSAT. Avoid them by decisively choosing to eliminate, defer, or select each answer after you read it once (or twice).

[Learn more about how to eliminate, defer, or select answers.][answers]

## Step 5: Move On or Revise

Ideally, you don't need this 5th step.

But you can't always make 4 eliminations or 1 selection. Sometimes you'll make 5 eliminations. And sometimes you'll only make 3, or even fewer, eliminations.

When you reach this point, the first steps are...

- **Flag** the question for later review, and
- [Reset].

Then, you can make a decision about what to do next:

1. **Move on** to the next question; or
1. **Revise** your analysis of the argument or the answers.

Moving on may feel lame, but it's one of the best ways to save time in the Reasoning section. And with those time savings you can potentially come back later, with fresh perspective.

If you do choose to *revise* then you must truly change your approach. Whatever you did the first time didn't work. If you're going to stick with this question, do something different.

{% capture summary %}
Note: Generally it's better to revisit the argument, rather than the answers.
{% endcapture %}
{% capture details %}
There's always the chance that you misread an answer, but usually struggling on a question means you haven't properly understood the argument OR you made the wrong level of prediction.
{% endcapture %}
{% include details.html %}

[Learn more about moving on and revising.][revise]

[1]: ../assets/images/LRanatomy.png
[2]: https://forms.gle/guG7HsDZXvEaydJ36
[break]: reason/break.html
[boil]: reason/boil.html
[answers]: reason/answers.html
[reset]: ../time/resets.html
[revise]: reason/flag.html
[family]: reason/job.html#family
[predict]: reason/predict.html
[validity]: reason/flaws.html
