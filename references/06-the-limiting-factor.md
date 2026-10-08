# 06 · Find the limiting factor

> "I just repeatedly tackle the limiting factor. Whatever the limiting factor is on speed, I'm going to tackle
> that. If capital is the limiting factor, then I'll solve for capital. If it's not the limiting factor, I'll
> solve for something else." [DW 00:00:00]

**The move:** at any moment, one thing limits progress. Name it, work on it, and expect it to move. He has
said the same in 2023: there's always "some kind of limiting factor to progress" [LEX400 01:15:29].

## It moves, so keep asking

His examples, across companies and years:

| Year | Where | The limiting factor, as he named it |
|---|---|---|
| 2018 | Tesla Model 3 | The production line, then delivery logistics [TED22 33:46] [X 2018-09-17](https://x.com/elonmusk/status/1041500594467270656) |
| 2021 | Starship | Getting to orbit first; doors and other features could wait [SB2 28:01 to 28:19] |
| 2023 | Starship launch | "the limiting factor for SpaceX for Starship launch is regulatory approval" [LEX400 01:16:42] |
| 2023 | AI compute | Chips, then transformers, then electricity, in that order over two years [LEX400 01:12:13] |
| 2024 | AI training cluster | Cabling, and "extreme power jitter" [LEX438 00:50:52, 00:49:56] |
| 2026 | Starship | "the heat shield be reusable": landing, refilling and flying again without inspecting 40,000 tiles [DW 01:44:16] |
| 2026 | Power for AI | Gas turbines, and within them "The limiting factor is the vanes and blades" [DW 00:00:00] |

The 2026 power case shows the drill-down. Electricity output outside China is roughly flat while chip output
grows "pretty much exponentially" [DW 00:00:00]. Ask why you can't build power plants, and the answer is
turbines. Ask why turbines are late, and it's one cast part made by a handful of suppliers. His conclusion: the
most economical place for AI compute will be space within about three years, because solar panels there get
about five times the power and need no batteries [DW 00:00:00]. That forecast is his; we include it as an
example of the method, not as a prediction we endorse.

## Spend your time where the limit is

> "I actually allocate time according to where the limiting factor. Where are things problematic? Where are we
> pushing against? What is holding us back?" [DW 01:44:16]

The corollary, in his account: teams whose work is going well see little of him, and teams on the limiting
factor see a lot [DW 01:44:16].

He says the detail he drills into is never arbitrary: "it is the limiting factor" [DW 01:44:16]. And he goes to
the floor: on the training cluster, he connected fibre optic cables himself [LEX438 00:50:52].

## Win on the variable that dominates

> "If a car is not fast, then if, let's say, it's half the horsepower of your competitors, the best driver will
> still lose. If it's twice the horsepower, then probably even a mediocre driver will still win."
> [LEX438 00:35:35]

---

## How to find it (our suggestion)

1. **Write the goal as a rate**: units per week, customers per month, launches per year.
2. **List every input** that rate depends on: people, money, parts, approvals, demand, a supplier.
3. **For each, ask: if this doubled tomorrow, would the rate go up?** The one where the answer is clearly yes
   is the limiting factor. If none, you've drawn the line wrong.
4. **Drill down** until you reach a part or a person: *power* becomes *turbines* becomes *blades*.
5. **Put your own time there,** in his phrase "weekly and some things are twice weekly" [DW 01:44:16].
6. **Predict the next one.** When this limit goes, what stops you next?

### Worked scenario (fictional)

A B2B data tool wants to go from 40 to 100 new customers a month.

| Input | If it doubled, would sign-ups double? |
|---|---|
| Website visitors (3,000/month) | No: half of demo requests already wait |
| Sales calls (2 reps) | Partly |
| Onboarding engineers (1 person, 9 days per customer) | **Yes**: 40 a month is that person's ceiling |
| Pricing | No evidence |

Limiting factor: onboarding capacity. Drill down: 6 of the 9 days are spent writing custom data connectors. The
founder sits in on three onboardings, then the team builds the five most-requested connectors. Onboarding falls
to 3 days, and the ceiling to about 120 a month. Prediction for the next limit: sales calls. They hire the
third rep now, not after.

### Failure modes

- **A list of five limiting factors.** If you have five, you haven't found it.
- **A team, not a part.** *Engineering is slow* is not a limiting factor. *The one person who can approve
  database changes* is.
- **Solving it from a meeting room.** He goes to where it is.
- **Staying after it moves.** He spends less time on things going well. Most leaders keep visiting the last
  problem.

### Limits

His examples are physical: lines, turbines, tiles. In small companies the limit is often a person's time or a
single decision, which is easier to move and easier to hide. The 2026 space-compute forecast is a forecast.

**Use it now:** `templates/03-limiting-factor-log.md`, and `templates/06-engineering-review.md` to review it
weekly.

**Checks to run:**
1. What is the one thing limiting progress this week? Name it in one line.
2. Who is working on it right now? Have you done that work yourself?
3. What will the next limiting factor be once this one is solved?
4. What's your horsepower: the one variable where a 2x lead beats a better driver?
