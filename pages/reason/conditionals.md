---
title: Conditional Logic
cat: reason
permalink: reason/conditionals
---

Conditional logic was invented in the 20th Century by mathematician-philosophers who wanted to be able to say things so precisely that they couldn't be rebutted. These philosophers didn't succeed in finding THE TRUTH of THE UNIVERSE. But they did invent a language game that the LSAT loves to play.

Conditional logic often appears on MECHANICAL questions. Including [JUSTIFY][1], [MUST BE TRUE][2], [PARALLEL][3], and [RULE][4] questions.

*Practice Idea:* Diagram every Conditional you find. Don't worry about getting Points, just practice the diagramming muscle. Later, once you reliably get the diagram correct on paper, you can try to (sometimes) diagram in your head.

## What is Conditional Logic?

Consider an example:

> If you eat kale, then you will be healthy.

{% capture summary %}
What do we know from this statement?
{% endcapture %}
{% capture details %}
The rule means that everyone who eats kale must be healthy.
{% endcapture %}
{% include details.html %}

{% capture summary %}
Suppose we see Jay eating kale, do we know that they're healthy?
{% endcapture %}
{% capture details %}
Yes!
{% endcapture %}
{% include details.html %}

{% capture summary %}
Suppose we know that Kay is healthy, do we know that they eat kale?
{% endcapture %}
{% capture details %}
No!
{% endcapture %}
{% include details.html %}

Conditional logic is absolute, but also limited. There's lots we don't know.

We don't know that kale is the only way to be healthy. And we don't even know that anyone actually eats kale.

## Conditionals are rules.

Think about conditional rules as very precise and reliable machines.

The left side (sometimes called the *sufficient condition*) is the input.

The right side (sometimes called the *necessary condition*) is the output.

The machine activates when the input is true. When the input is true, we know the output is also true.

> Lee takes a bite of kale, we know they're healthy. 

*Note:* The bite of kale doesn't *cause* Lee to be healthy, but we still *know* Lee is healthy because our rule tells us that everyone who eats kale is healthy.

And the machine also activates when the output is false. When the output is false, the input must also be false.

> Mo is unhealthy, so we know Mo doesn't eat kale.

The machine always activates under these two conditions. It does not activate under any other conditions, or on its own.

> Neha eats spinach, we know nothing else.

> Ori is a healthy person, we know nothing else.

Conditionals are about *knowledge*. We know every time the input is true, that the output is also true.

## Contrapositives

Contrapositive = flip + negate.

"A --> B" contraposes to "not-B --> not-A"

The statement and it's contrapositive are logically identical That means: If a statement is true, then so is then contrapositive.

### "AND" contraposes to "OR"

"C AND D --> E" contraposes to "not-E --> not-C OR not-D"

For example...

> Sundaes require both Ice Cream and Fudge
>
> If it's missing Ice Cream or Fudge, then it's not a Sundae.

## Conditional Words:

If, All, Only If, Must, Without, Unless, None + any absolute word (whenever, always, never, no, requires, etc..)

Memorize these words and how to diagram them. Fill in the letters with ideas to make it stick.

### If A, then B

If introduces the left side (the sufficient condition). This is the same as:

- B if A
- All A are B
- Whenever A, B

Diagram:

> A --> B

### Only if X, then Y

Only If introduces the right side (the necessary condition).

This is the same as:

- Y only if X
- Y requires X

Diagram:

> Y --> X

(Caution: "Only" isn't the same as "Only If". "Only" tends to mean "All.")

### G without F

Without = If Not.

This is the same as:

- Without F, G
- Unless F, G

Diagram:

> not-F --> G

### No T are V

Diagram:

> T --> not-V

Misc. Diagramming Skills:

1. Keep the Same Ideas the Same when making the diagram.
1. Remove or qualify constants.
1. Use short words instead of letters/acronyms.
1. Keep the Facts and the Conclusion separate.

For example:

> If you truly love me, prove it. To prove that you love me, you must buy me a horse. So don't ask me out, unless you've bought me a horse.

{% capture summary %}
*This is a bad argument, do you what's missing (the Gap)?*
{% endcapture %}
{% capture details %}
"if you don't truly love me, then don't ask me out"
{% endcapture %}
{% include details.html %}

{% capture summary %}
Not seeing the gap, try to diagram it...
{% endcapture %}
{% capture details %}
 > *Fact:* True Love --> Prove Love
 >
 > *Fact:* Prove Love--> Horse
 > 
 > *Conclusion:* No Horse --> No Ask Out
{% endcapture %}
{% include details.html %}

{% capture summary %}
How'd we get that...
{% endcapture %}
{% capture details %}
1. "Prove that you love me" and "prove it" are the same idea. Same for horse buying.
1. "Love" and "me" are constants that appear in several different ideas.
1. Simplifying to "L -> P, P -> H, no-H --> no-O" might save space, but you'll have to constantly re-translate it.
1. Everything before the "so" is a Fact you must accept, no matter how strange. But you don't have to accept the Conclusion.
{% endcapture %}
{% include details.html %}

## How you use your Diagram changes depending on the question type.

### JUSTIFY Questions {#justifydiagram}

In a JUSTIFY question, diagram to find the Gap.

This strategy also works on DEPENDS questions with Conditional logic.

There are two types of Gaps.

Gap Type 1:
> *Fact:* A --> B
>
> *Fact:* B --> C
>
> *Conclusion:* A --> D

{% capture summary %}
What's the Gap?
{% endcapture %}
{% capture details %}
C --> D
{% endcapture %}
{% include details.html %}

Gap Type 2:
> *Fact:* X --> Y
>
> *Fact:* W --> Z
>
> *Conclusion:* X --> Z

{% capture summary %}
What's the Gap?
{% endcapture %}
{% capture details %}
Y --> W
{% endcapture %}
{% include details.html %}

### MUST BE TRUE questions {#mbtdiagram}

Your Job is to combine the Facts. Contrapositives may be useful.

For example, suppose we know:

> All monkeys are primates.
>
> Birds are not primates.

{% capture summary %}
Diagram:
{% endcapture %}
{% capture details %}
> Monkey --> Primate
>
> Bird --> not-Primate
{% endcapture %}
{% include details.html %}

Can you combine it?

{% capture summary %}
If you're struggling, try starting by doing one contrapositive:
{% endcapture %}
{% capture details %}
> Monkey --> Primate
> 
> Primate --> not-Bird
{% endcapture %}
{% include details.html %}

{% capture summary %}
See the combo now?
{% endcapture %}
{% capture details %}
> Monkey --> not-Bird
{% endcapture %}
{% include details.html %}

### PARALLEL Questions {#paralleldiagram}

Your Job is to extract the Argument's Structure and find the same Structure in the Answers.

For example:

> *Fact:* R
>
> *Fact:* R --> S
>
> *Conclusion:* S

is the same structure as:

> Water is a liquid. All liquids flow. Therefore, water flows.

and, even though the order and keywords differ it's also the same as:

> I feel good since I drank coffee today. Every day I drink coffee, I feel good.

and the same as:

> *Fact:* not-T
>
> *Fact:* not-T --> not-U
>
> *Conclusion:* not-U

### RULE Questions {#rulediagram}

On RULE questions, you diagram the Rules given in the Facts. (As an INFER Family question, there's not actually an Argument.)

Diagraming the Rule lets you know what you can prove and how you can prove it.

1. We can only prove the idea on the right side (the output).
1. We can prove it when the left side (the input) happens.

For example, consider this rule:

> Entering private property is a trespass if you don't have permission.

{% capture summary %}
Diagram:
{% endcapture %}
{% capture details %}
> Enter private property & not-permission --> Trespass
{% endcapture %}
{% include details.html %}

{% capture summary %}
What can we prove? What can we not prove?
{% endcapture %}
{% capture details %}
We can prove trespass. But we cannot prove that anyone didn't trespass.
{% endcapture %}
{% include details.html %}

Now, consider these three answers:

1. H wasn't trespassing because it was government property.
1. When L entered K's private property they were trespassing because they did not have permission.
1. G trespassed because they did not have permission.

{% capture summary %}
Which are wrong and which are right? Why?
{% endcapture %}
{% capture details %}
1. Incorrect. It's unprovable ("wasn't trespassing").
1. Correct. Provable (yes "trespassing") and Proved (private + not permission).
1. Incorrect. It's provable (yes "trespassed"), but it doesn't follow the rule (we need both parts to satisfy the "and").
{% endcapture %}
{% include details.html %}

[1]: #justifydiagram
[2]: #mbtdiagram
[3]: #paralleldiagram
[4]: #rulediagram