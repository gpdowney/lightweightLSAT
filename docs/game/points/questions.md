# Game Question Types

There are 3 major question types in the Games section:

Major Type | Example | Basic Approach
-- | -- | --
[LIST](#list) | "Which of the following could be a complete and accurate list...?" | Go rule-by-rule. Use each rule to eliminate one answer.
[IF](#if) | "If X is in 3, then which of the following...?" | Add the new information to a fresh board, then follow the rules to make a hypo.
[WHICH](#which) | "Which of the following must be false?" | Reuse old hypos. Make new hypos to test remaining answers, if needed.

Do them in this order: LIST, IF, then WHICH.

*Knowing how to solve the major types is enough to get you through most questions in most games.*

When in doubt, any question can be approached as if it was a WHICH question.
In other words, you can always test answers.

When you're ready to add complexity to your system, there are also 4 minor question types:

Minor Type | Example | Basic Approach
-- | -- | --
[DOMINOS](#dominos) | "Which of the following, if true, determines the position of every other element?" | Test answers until one makes every element fall into place.
[hard IF](#hard-if) | "If X is before Y, then which one of the following...?" | Make mini-splits based on the new information. Or treat like WHICH.
[hard LIST](#hard-list) | "Which of the following is a complete and accurate list of the places that X could go?" | Reuse old hypos to eliminate incomplete answers.
[SUBSTITUTE](#substitute) | "Which of the following rules, if substituted for the rule...?" | Use old hypos to eliminate answers that could be false.

Order matters less for these minor types.
Generally do them at the same time as WHICH questions.

More details on each type below...

***

## LIST

> Which of the following could be a complete and accurate list of toppings on the pizza?

The LIST question is typically the first question of a game.

To solve them, use one rule at a time to eliminate answers.
Usually each rule will eliminate 1 answer.

!!! tip "LIST questions have 4 upsides"

    1. The correct answer is a valid hypo you can use on future questions. Write it down.
    1. Going rule-by-rule to answer the LIST question gives you a chance to double-check that you wrote the rules clearly and correctly.
        1. If you have to look back at the situation, then you didn't symbolize the rules clearly or neatly enough.
        1. If you can't make 4 eliminations, then you either missed a rule or messed up a rule.
    1. Quickly glancing at the the LIST during the [scan] can give you clues about how to draw the game. 
        1. The format of the answers could be a model for how you draw your board.
        1. The question often indicates whether the elements are ordered or grouped.
    1. LIST questions are good practice for smoothly following rules one-by-one.

## IF

> If there are no canaries in the coal mine, what must be true?

IF questions give you a starting point for a hypo.

To solve IFs...

1. Draw a fresh board with the new info.
1. Follow the next, overlapping rule.
1. Add new info to the board.
1. Repeat steps 2 + 3 to exhaustion (of the rules).
1. Ask "Who's left?"
1. Use the hypo to eliminate or select answers.

??? info "Risky advanced move"

    Instead of completing the hypo, check the answers each time you add new information to the board.

    Upside: you save a few seconds that you would have spent finishing the hypo.

    Downsides: your hypo is less useful in the future; and if it doesn't work out, then you lost time checking the answers more frequently.

## WHICH

> Which of the following must be true?

!!! note "Reminder"

    Do the WHICH questions after you've made hypos on the IF questions

To solve WHICHes...

1. Reuse your old hypos to prove or disprove answers.
1. Wizard for 10 seconds maximum: Stare at the remaining answers to see if any are obviously correct or incorrect.
1. Make new hypos to prove or disprove the remaining answer.

??? info "Advanced move"

    Test answers strategically...
    
    - For *must be*: start by testing the answers you think are wrong.
    - For *could be*: start by testing the answers you think are right.

## DOMINOS

> Which one of the following, if true, determines the pecking order of the chickens?

!!! note "Terminology note"

    I call these questions DOMINOS because the correct answer will make every element fall into place like a cascade of dominos.

Approach to DOMINOS:

1. Test each answer, starting with (a).
1. As soon as there's an ambiguity, move on to the next answer.
1. If the board completely fills out, and every move was required, choose that answer.

??? example

    Elements: `W, X, Y, Z`
    
    Rule 1: `X` must be next to `Y`
    
    Rule 2: `X` must be after `Z`

    Question:

    > 1. Which of the following completely determines the order of the elements?
    >       1. `W` in 3.
    >       1. `Y` in 2.
    >       1. `X` in 4.

    Start at the top (a): `_ _ W _`

    Notice that `W` isn't connected to any rules. 
    Yikes.
    
    Move on to the next answer choice (b): `_ Y _ _`

    Notice that rule 1 means `X` *could* go before or after `Y`.
    That's ambiguous.

    Move on to the next answer choice (c): `_ _ _ X`

    Apply rule 1: `_ _ Y X`

    Notice that rule 2 is taken care of.
    `Z` will always be before `X`.

    But since you're so close and already did all this work, visually complete the hypo for future questions: `(W Z) Y X`

    This disproves (c).
    Eliminate (c).

    Go back to (a): `_ _ W _`

    Notice that rule 1 means `(X Y)` need 2 consecutive spaces.

    Apply rule 1: `(X Y) W _`
    
    Notice this will always break rule 2.
    `X` is always before `Z`.
    Cross out the hypo.
    Eliminate (a).

    Choose (b).
    Or, for fun because you're not doing race practice, see why it works: `_ Y _ _`

    Rule 1 seemed ambiguous last time, see if rule 2 is useful, even if `Y` isn't in it.

    Notice that rule 2 means `X` can't go first, so it has to go 3rd: `_ Y X _`

    And then apply rule 2: `Z Y X _`

    Good news, there's only 1 spot left for `W`, the leftover: `Z Y X W`

    Ta da! 
    Every element was required to go where it went. 
    You proved (b) is correct.

??? tip "Advanced move"

    Start with answers that put elements involved in multiple rules in places that make them uncomfortable.
    
    In the above example, I would have started with (c) because `X` is involved in both rules and being at the edge of the board is uncomfortable.

    I would have tried (b) next. I wouldn't want to test (a) because `W` is a leftover, there are no rules attached to it.

!!! warning

    Old hypos are not useful on DOMINOS questions.
    
    This is annoying because it means you need to make more hypos.
    It also means DOMINOS can be worth doing before WHICHes.

## hard IF

> "If you don't eat your dinner..."

On hard IFs, you can't easily follow the rules to complete the hypo.

IFs can be hard when they involve...

- Anti-placements (like "If `G` not in 1...")
- New rules instead of placements (like "If `G` is before `H`...")

Options for dealing with hard IFs:

1. Pretend it's a WHICH (but don't forget about the new restriction)
1. Write the new rule down, try to connect the other rules in the abstract, without putting elements on the board.
1. Mini-[splits]: Often the new restriction will limit the game to 2 or 3 options. Making splits can be a good way to keep moving.

## hard LIST

> "Which of the following is a list of all the movies X could see?"

The first clue that a LIST question is hard is that it isn't the first question.

But the actual distinction is this:

- LIST = "what could be a list" = one hypo
- hard LIST = "list of what could be" = all the possibilities across every hypo

Old hypos are very useful for hard LIST questions.

1. Collect the relevant information from old hypos.
1. Eliminate incomplete answers.
1. Make new hypo(s) to test the remaining answers.

??? example

    Question: 
    
    > 1. "Which of the following is a list of all the places that `L` could go?"
    >       1. 1
    >       1. 1, 2
    >       1. 1, 2, 4
    >       1. 1, 2, 3
    >       1. 1, 2, 3, 4

    old hypo 1: `L M A O`
    
    old hypo 2: `M A L O`

    Step 1, collect relevant info: 
    You've seen `L` in 1 and 3. 
    Write that down.
    
    Step 2, eliminate incomplete answers: 
    (a), (b), and (c) are missing 3.
    Eliminate them.

    Step 3, test remaining answers: 
    The difference between (d) and (e) is 4. 
    Start a new hypo with `L` in 4.
    
    - If it works, select (e) because (d) is incomplete.
    - If it breaks, select (d) because (e) is incorrect.

## SUBSTITUTE

> Which of the following rules, if substituted for the rule against perpetuities, would have the same effect on the neoliberal order?

!!! note "Terminology note"

    You may have heard other students call these "Rule Substitutions" with much fear and trembling.

You need not fear these monsters, here's how to approach SUBSTITUTEs:

1. Use old hypos to eliminate answers that *could be false*.
1. Guess from the remaining answers, OR
1. Try to disprove each remaining answer by creating a hypo that...
    1. follows the new rule (the rule proposed in the answer), and
    1. breaks the old rule (the rule being substituted out), and
    1. follows all the other rules.

Step 1 works because the new rule must have the exact same effect as the old rule.
So if you have an old hypo where the new rule isn't true, then that new rule can't possibly have the same effect.

Step 2 offers a bail-out point because step 1 is usually quick, but step 3 can be much more intensive and you might be tight for time.

Step 3 works for similar reasons as step 1.
If you can follow the new rule while breaking the old rule then they aren't the same.

!!! tip

    Some questions that look like SUBSTITUTEs are actually hard IFs.

    For example:
    
    > If the rule that "U must be first" is replaced by the rule that "W must be first", then which one of the following...

    There's a chance you can solve this question by...
    
    1. drawing a new board with the new info (here, put W in 1), and then 
    2. following all the other rules except the replaced rule (here, ignore "U in 1").

!!! warning "Wizards beware"

    Wizards tend to tangle up the rules with their magic insights.
    The process for solving SUBSTITUTIONs will be easier if you skipped making [connections] and [splits] upfront.

    Wizards are also at a disadvantage on SUBSTITUTIONs because they're hard to solve via staring.
    It's extra challenging to mentally juggle losing an old rule plus gaining a new rule.

    *Sometimes* you can wizard a SUBSTITUTION question because one of the answers is a sneaky re-wording of the old rule.
    But watch out for answers that are just slightly mis-worded.

[scan]: ../draw/draw.md#scan
[splits]: ../draw/splits.md
[connections]: ../draw/connections.md
