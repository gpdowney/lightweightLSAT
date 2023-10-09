# A Hypo Walkthrough

This page walks you through how an extended example of making and using hypos to get points.

The first part emphasizes the importance of making new hypos one **overlapping** rule at a time. The second part emphasizes the proper **re-use** of old hypos.

To get the most value out of this page, write down your answers to the questions posed below before you click to expand them.

A standard order game:

Elements: `t w x y z`.

Rule 1: `w` must be next to `x`

Rule 2: `t` goes before `y`

## Part 1: Making hypos using overlap

Question 1:

> 1. If `t` is in 3, what could be true?
>       1. `z` is in 2
>       1. `z` is in 1
>       1. `z` is in 4
>       1. `w` is in 3
>       1. `x` is in 3

??? question "What's the first thing you do?"

    Make a new number line and put `t` in 3rd, because this is [an IF question][if].

    `_ _ t _ _`

??? question "Which rule should you look at first?"

    Rule 2 overlaps with `t,` and you have `t` on the board.

    So you can add `y` in a cloud after `t`

    `_ _ t ( _ y )`

??? question "What's next?"

    Take care of the only remaining rule, rule 1.

    There's not enough space for `(w x)` after `t`, so they must go before, also in a cloud since they could go in either order.

    `( w x ) t ( _ y )`

??? question "Once you've taken care of all the rules, what should you do?"

    Ask yourself: "Who's left?"

    `z` is leftover. 
    The only available space for `z` is in the cloud with `y`.

    `( w x ) t ( z y )`

??? question "How should you use your hypo to evaluate the answers?"

    Since this is a "could be true" question, you want to find the answer that happens in our hypo.
    When you see the answer in our hypo, you can select that answer and move on.

??? question "Ok, now evaluate the answers!"

    `( w x ) t ( z y )`

    === "(a) `z` is in 2"
        Don't see it.
        Next.

    === "(b) `z` is in 1"
        Didn't happen.
        See ya.

    === "(c) `z` is in 4"
        There it is!
        Select (c) and move on to the next question.

    === "(d) `w` is in 3"
        Didn't need to look at this one.

    === "(e) `x` is in 3"
        Really wasting time looking at these extra answers after you found the correct one.

        Did you not trust your hypo?
        Is that lack of trust justified?
        
        Or did you start here because you have some (incorrect) superstition about (e) being correct more often than (a)?

## Part 2: Re-Using Hypos

Question 2:

> 1. Which of the following must be true?
>       1. `t` is before `z`.
>       1. `t` is not last.
>       1. `w` is before `x`.
>       1. `x` is not first.
>       1. `y` is before `z`.

??? question "What do you know about (a)?"
    In the hypo, `t` is before `z`. So (a) could be true. Whether it must *always* be true, you don't know.

    Defer on (a).

??? question "What do you know about (b)"
    In the hypo, `t` is not last. That proves that (b) *could* be true.

    Defer on (b) also. *But don't be discouraged!*

??? question "What do you know about (c)?"
    In the hypo, `w` could be before or after `x`. That proves that (c) *could be true* and that it *could be false*. Because it could be false, it doesn't need to be true.

    Eliminate (c).

??? question "What do you know about (d)?"
    In the hypo, `x` can go in `1`. That proves (d) could be false.

    Eliminate (d).

??? question "What do you know about (e)?"
    In the hypo, `y` can come after `z`. That proves (e) is not always true.

    Eliminate (e).

??? question "Do you see the right answer?"

    At this point, with 2 answers remaining, you might allow yourself a quick moment to try to be a wizard. 
    
    In this case, being a wizard means staring at the rules and at the remaining answers hoping that the right answer will magically appear.

    Because you've narrowed down the options, there's less to think about and it might be clear to you which answer is correct.
    
    !!! warning

        Don't spend more than 5-10 seconds as a wizard. 
        When the magic doesn't flow, start making more hypos.

??? question "If you don't magically see the right answer, what can you do?"

    Make new hypos that *disprove* the wrong answers, because this is a "must be" question.

    ??? question "What would disprove (a)?"
    
        `t` after `z`

        There are many ways to make `t` come after `z`.
        Unlike making last hypo, there's no clear starting place.

        === "Option 1: random start"
            Don't waste time.
            Start making a hypo with `t` after `z`.
            
            If the hypo doesn't work out, use the insight you just gained by making that broken hypo to pick a better starting point.
            Or, perhaps, you now suspect it will never work out, in which case move on to the next answer.

        === "Option 2: *smart* start"
            A "smart" first move increases the chance that you'll be able to follow all the rules and make a valid hypo.

            Here putting `z` first would make sure that `t` is always after, and it gives the `(w x)` cloud plenty of space to be together.

            `z _ _ _ _`

            take care of `(w x)`: `z (w x) _ _`

            take care of `t-y`: `z (w x) t y`

            Since we took care of all the rules, this is a valid hypo that disproves (a)
    
    ??? question "What would disprove (b)?"

        Nothing. 
        By eliminating (a) above, you proved that (b) is the correct answer.
        That means (b) must be true.
        Trying to disprove it will be futile.
        Trying to prove it would be exhausting.

### Reflection Questions

??? question "When is it OK to put an element in a random place?"

    When you made the hypo to test answer 2(a), you could risk an arbitrary move because you only needed that hypo to work out once to disprove the answer.

    When you made the hypo for the IF question, you had 5 answers that hypo needed to work for.
    Had you gone down one random path, you would have limited your chances of creating a hypo that would help for all 5 answers.
    Also, you didn't have to make a random choice on the IF because you could use clouds to get the elements on the board.

??? question "Could you have reversed order and used the hypo you made on question 2 to solve question 1?"

    Not in this case.
    At least not with the hypos suggested here.

    Question 1 started: "If `t` is in 3...".

    The hypo for question 2 (for the *smart* start) was `z (w x) t y`. 
    In that hypo `t` is in 4, so it doesn't meet the requirement of the IF.
    
    You can always reuse work from IF questions the WHICH questions, but the reverse isn't true.
    WHICH questions ask about every possible situation, and that includes the limited situation of the IF question.
    This is another reason to do IF before WHICH.

## Takeaways

### For making hypos

1. Don't randomly follow rules. Follow the rule that *overlaps* with the elements you've already added to the board.
1. Don't make assumptions. Don't put an element somewhere just because it *could* go there. Use clouds to add what you know without committing to one arbitrary path. This flexibility makes your hypos more useful.
1. Notice what rules are taken care of. If you completely followed a rule or it can't be broken, then you don't need to worry about that rule for the rest of that hypo.
1. When you're out of rules, ask: "Who's left?"

### For re-using hypos

1. Reuse your hypos on future questions to get nearly free points, or at least free eliminations.
1. Know what you want from the hypos before you look at them. For example, literally say to yourself: "I want to see `t` in last to disprove (b)"
1. Keep moving. When you get stuck, start writing out hypos. Getting your pencil moving making hypos, even ones that don't work, will help your brain figure out how the game works.
1. You can always use hypos from IFs on WHICHes, but not vice versa. This is another reason to do IFs before WHICHes.

[if]: questions.md#easy-if
