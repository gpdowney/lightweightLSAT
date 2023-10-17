# Splits

A game can be "split" when it can only go a few ways.

!!! example "Option rules create splits"

    Suppose we have a game with an [option rule]: `A must go in 2 or 4`

    This gives us a 2-way split:

    1. `_ A _ _` or
    2. `_ _ _ A`

!!! Danger "Splits =/= hypos"

    Hypos only represent *some* of the possibilities.

    Splits map out *every* possibility.

## Drawing splits

If you notice a promising split during your [scan], then you can use the split to make your initial drawing more efficient.
Instead of drawing a single board, draw each split.
If the split takes care of a rule, then you can skip drawing those rules.

You may also notice splits during a [check-for] or once you start doing the questions.

!!! example "Mini-Splits"

    Some questions create mini-splits specific to that question.
    This is common on [hard IF questions][hardIF].

    Elements `F, G, H, L`

    Question: `If F is not in first or second, which must be true?`

    Split:

    1. `_ _ F _` or
    2. `_ _ _ F`

### Step 1: Outline the options

Sketch out each split before you add-in other rules or elements.

This will help make sure your splits are exhaustive and you don't forget where they started.

### Step 2: Add in other rules and elements

Follow the rules to fill out as much of each split as you can.

Useful splits will take care of more rules, either by triggering the rule or ensuring that it can't be broken in every split. If a rule is taken care of in every split, then you don't need to worry about it for the rest of the game.

??? example "Splits, step-by-step"

    Elements: `R, S, T, V`

    Rules:
    
    1. `R must go before S but R cannot go immediately before S`
    2. `T goes immediately before or after S`

    The first rule means `R` can't go in 3 or 4, because that wouldn't leave room for `S`.
    `R` must go in 1 or 2.

    Initial outline:

    1. `R _ _ _` or
    2. `_ R _ _`

    Add `R-_S` rule:

    1. `R _ (S _)`
    2. `_ R _ S`

    We can't add the `(ST)` rule in the first split, because we don't know where `S` goes.
    But we could split the first split to pin down `S` and try to get `T` in.

    1. `R _ S _`
    2. `R _ _ S`
    3. `_ R _ S`

    Add `(ST)` rule:

    1. `R _ S _`
    2. `R _ T S`
    3. `_ R T S`

    For split 1, we don't know where `T` will go, but we do know it will always be next to `S` so that rule is taken care of.

    Add the last remaining element, `V`:

    1. `R T/V S V/T`
    2. `R V T S`
    3. `V R T S`

    Ta da! By splitting, we've completely solved the game.

## What splits are worth drawing?

Drawing splits is a time investment.
They aren't always a good use of time.

!!! tip "Puzzle practice suggestion: split every game"

    Try to find multiple ways to split every game you see. 
    Split even if it seems like an unproductive 8-way split.

    Learning what splits aren't helpful is a good way to build your intuition for what splits are helpful.

    When you're done, record what makes splits worthwhile and the specific clues that suggest a split.

Splits are generally worth drawing out when...

1. there are only 2-3 options, and either
2. it takes care of a tricky rule, or
3. connects with other rules.

!!! example "Always split biconditional rules"

    Biconditionals are tricky and spitting takes care of them.

    Rule: `Either X or Y must be included, but not both`

    Split:

    1. `Yes X / No Y` or
    2. `No X / Yes Y`

[hardIF]: ../points/questions.md#hard-if
[option rule]: ../points/questions.md#option
[Biconditional rule]: ../points/questions.md#iconditional
[scan]: draw.md#step-1-scan
[check-for]: draw.md#step-3-check-check
