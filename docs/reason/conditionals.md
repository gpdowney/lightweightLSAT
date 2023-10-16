# Conditional Logic

Conditional logic was invented in the 20th Century by mathematician-philosophers who wanted to be able to say things so precisely that they couldn't be rebutted. These philosophers didn't succeed in finding *the truth of the universe*. But they did invent a language game that the LSAT loves to play.

Conditional logic typically indicates that a question is MECHANICAL in style.

!!! tip "Practice idea"

    Draw every conditional you find. Don't worry about getting points, just practice the diagramming muscle. Later, once you reliably get the diagram correct on paper, you can try to (sometimes) diagram in your head.

## What is conditional logic?

!!! example

    If you eat kale, then you will be healthy.

    `Kale --> Healthy`

    === "What do we know from this statement?"
        The rule means that everyone who `eats kale` must be `healthy`.

    === "Suppose we see Jay `eating kale`, do we know that they're `healthy`?"
        Yes!

    === "Suppose we know that Kay is `healthy`, do we know that they `eat kale`?"
        No! We don't know that `kale` is the only way to be `healthy`.
    
    === "Do we know that anyone eats `kale`?"
        Nope! We just know what happens *if* someone eats kale.

Conditional logic is absolute, but also limited. There's lots we don't know.

## Conditionals are rules

Think about conditional rules as very precise and reliable machines.

The left side--sometimes called the ***sufficient condition***--is the input.

The right side--sometimes called the ***necessary condition***--is the output.

The machine activates when the input is true. When the input is true, we know the output is also true.

!!! example

    When we see Emm take a bite of kale. We 100% know they're healthy

    Note: The bite of kale doesn't *cause* Emm to be healthy, but we still *know* Emm is healthy because our rule tells us that *everyone* who eats kale is healthy.

And the machine also activates when the output is false. When the output is false, the input must also be false. This is called the ***contrapositive***.

!!! example

    We know Mo is unhealthy. That means we can also be 100% sure Mo doesn't eat kale.

The machine always activates under these two conditions. It does not activate under any other conditions, or on its own.

!!! example

    Neha doesn't eat kale, we know nothing else.

    Ori is a healthy person, we know nothing else.

    Popeye eats spinach, we know nothing else.

Conditionals are about *knowledge*. We know every time the input is true, that the output is also true.

## Conditional words

Conditional words include more than `If X, then Y.`

Any absolute statement can be written as a conditional.

!!! example

    If absolute, then conditional

So absolute words like `all`, `none`, `always`, `never`, and `whenever` are all conditional words.

The other important conditional words are `only` and `unless` / `without`.

In addition, `and` and `or` play a special role in conditional statement.
When you contrapose `and` it becomes `or` and vice versa.

??? example

    Model 1: If A, then B or C.

    Contrapositive: If not B and not C, then not A.

    Example 1: If you eat ice cream, then you will be cold or happy.

    Contrapositive: If you are not cold and not happy, then you did not eat ice cream.

    Model 2: If X and Y, then Z.

    Contrapositive: If not Z, then not X or not Y.

    Example 2: If you are on-time and good at your job, then you will get a promotion.
    
    Contrapositive: If you did not get a promotion, then you were not on-time or not good at your job.

## Drawing conditional diagrams

It can be useful to draw abstract versions conditional statements.
These conditional diagrams help you keep track of the direction of the arrows and combine conditional statements.

!!! tips "Diagramming tips"

    1. Keep the same ideas the same when making the diagram.
    1. Remove or qualify constants.
    1. Use short words instead of letters/acronyms.
    1. Keep the facts and the conclusion separate.

### If A, then B

If introduces the left side (the sufficient condition). This is the same as:

- B if A
- All A are B
- Whenever A, B

Diagram:

    A --> B

### Only if X, then Y

Only if introduces the right side (the necessary condition).

This is the same as:

- Y only if X
- Y requires X

Diagram:

    Y --> X

(Caution: "Only" isn't the same as "Only If". "Only" tends to mean "All.")

### G without F

Without = if not.

This is the same as:

- Without F, G
- Unless F, G

Diagram:

    not-F --> G

### No T are V

Diagram:

    T --> not-V

## How to use conditional logic depends on the question

### MECHANICAL-HELP

In a MECHANICAL-HELP question, you diagram to find the gap.

!!! note

    This strategy also works on DEPENDS questions that have conditional logic.

There are two types of gaps.

=== "Gap type 1"
    Fact: A --> B

    Fact: B --> C

    Conclusion: A --> D

    ??? question "What's the gap?"

        C --> D

=== "Gap type 2"
    Fact: X --> Y

    Fact: W --> Z

    Conclusion: X --> Z

    ??? question "What's the gap?"

        Y --> W

### MECHANICAL-INFER

Your job is to combine the facts.
Contrapositives may be useful.

Try to diagram and combine this:

??? example "All monkeys are primates. Birds are not primates."

    Fact 1: `Monkey --> Primate`

    Fact 2: `Bird --> not-Primate`

    Combo: `Monkey --> not-Bird`

### PARALLEL

Your job is to extract the argument's structure and find the same structure in the answers.

Generally, you'll should diagram the argument.
You may need to also diagram answer choices that seem close until you find an exact match.

!!! example

    Fact: R

    Fact: R --> S

    Conclusion: S

    is the same structure as:

    > Water is a liquid. All liquids flow. Therefore, water flows.

    and, even though the order and keywords differ it's also the same as:

    > I feel good since I drank coffee today. Every day I drink coffee, I feel good.

    and is also the same as:

    > not-T
    >
    > not-T --> not-U
    >
    > therefore, not-U

### RULE Questions

On RULE questions, you diagram the rule(s) given in the facts.

Diagraming the rule(s) lets you know what you can prove and how you can prove it.

1. We can only prove the idea on the right side (the output).
1. We can prove it when the left side (the input) happens.

Diagram this rule:

??? question "Entering private property is a trespass if you don't have permission."

    Diagram: `private property & not-permission --> trespass`

??? question "What can we prove? What can we not prove?"

    We can prove someone guilty of trespass. We have a rule that tells us when someone is trespassing.

    We *cannot* prove someone is innocent of trespass. We don't have a rule that proves that someone didn't trespass.

Evaluate these answers:

??? question "H wasn't trespassing because it was government property and they didn't have permission."

    Incorrect because `wasn't trespassing` is unprovable.

??? question "When L entered K's private property they were trespassing because they did not have permission."

    Correct because `trespassing` is provable and it met the two conditions `private` and `not permission`

??? question "G trespassed because they did not have permission."

    `trespassing` is provable, but this is incorrect because we're missing `private property`, one of the requirements.
