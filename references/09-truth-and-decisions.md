# 09 · Truth and decisions

This chapter turns his remarks on truth into a decision method. The method is ours; the anchors are his.

## Obsessed with truth

> "I was just absolutely obsessed with truth. Just obsessed with truth. And so the obsession with truth is why I
> studied physics, because physics attempts to understand the truth, the truth of the universe." [TED22 46:12]

## Foundations first

> "If you cannot count on the foundational physics being correct, obviously the inventions are simply wishful
> thinking, imagination land. Magic basically." [LEX400 00:37:02]

He separates the two: physics is about how reality works, engineering is "inventing things that have never
existed", and engineering has the far wider range of possibilities [LEX400 00:38:38]. **Our reading:** check
which of your assumptions are physics (fixed) and which are engineering (open), before you argue about the
plan.

## Weigh decisions by what they're worth

> "But the marginal value of a better decision can easily be, in the course of an hour, a hundred million
> dollars." [LEX438 01:18:32]

He looks at outcomes "on a percentage basis", because in absolute terms "I would never get any sleep"
[LEX438 01:19:29]. **Our reading:** spend decision time in proportion to the value at stake, and judge choices by
how much they move the odds, not by the size of the number.

## Look for agreement across disagreement

On X's Community Notes, he explained that a note is only shown when people who have historically disagreed both
rate it well [LEX400 01:45:33]. His comment on why that works:

> "It makes sense that if people who in the past have disagreed, agree about something, it's probably true."
> [LEX400 01:46:11]

**Our reading:** inside a team, the claims your sceptics and your optimists both accept are the safest
foundation.

## Seek the negative

He advises paying attention to negative feedback and asking for it, "particularly from friends", which he says
"hardly anyone does" [TED13 19:19].

## Know when to change course

He takes drastic action "only when I conclude that success is not in a set of possible outcomes" [DW 01:44:16],
judged from a run of weekly data points, not one meeting.

---

## The decision method (our suggestion)

Use it for any decision worth more than a day of someone's time.

1. **State the decision** and the value at stake (money, time, customers). That value sets how long you spend.
2. **List the assumptions** it rests on. Mark each as physics (fixed: maths, law, measured data) or engineering
   (open: what we could build or change).
3. **Test the foundations.** For each fixed assumption, what's the evidence? If none, it's not a foundation.
4. **Put a probability on the outcome** you expect, as a percentage, not "likely".
5. **Find agreement across disagreement.** Ask the person most likely to disagree. Keep what you both accept.
6. **Ask for the negative.** One friend, one question: *what am I wrong about?*
7. **Decide, log it,** and set the date you'll check the result. Compare the outcome with your percentage.

### Worked scenario (fictional)

A 12-person SaaS company is deciding whether to rebuild its billing system: four engineer-months, and billing
errors cost about $30,000 a quarter in refunds and churn.

| Assumption | Physics or engineering? | Evidence |
|---|---|---|
| Errors cost $30k a quarter | Physics (measured) | Refund log, 4 quarters |
| Errors come from the billing code | Engineering (a guess) | None yet |
| A rebuild fixes them | Engineering | None |

The foundation is weak: nobody has checked where the errors start. A day of log review (worth it for a $120k a
year problem) shows 70% start from manual plan changes made by support. The sceptic (the CTO, who opposed the
rebuild) and the optimist (the head of support) both agree on that. The decision becomes: delete manual plan
changes (chapter 02), 60% confidence it halves refunds, check in one quarter. The rebuild waits.

### Failure modes

- **Arguing about engineering before checking physics.** The plan is wishful thinking if the base is
  wrong.
- **Words instead of numbers.** *Probably* can't be checked later; 60% can.
- **Asking only allies.** Agreement among people who already agree tells you little.
- **No check date.** Without it, you never learn whether you were calibrated.

### Limits

He made these remarks about physics, AI and online fact-checking, not as a business method. The step-by-step
method is ours, assembled from them.

**Use it now:** `templates/08-decision-check.md`.

**Checks to run:**
1. What would make your current plan "wishful thinking, imagination land" [LEX400 00:37:02]? Which foundation is untested?
2. Which decision this week deserves more than an hour, given what it's worth?
3. Where do people who usually disagree with you agree? Start there.
