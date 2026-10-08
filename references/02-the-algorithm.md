# 02 · The algorithm: five steps, in order

> "I have this very basic first principles algorithm that I run kind of as a mantra." [LEX438 00:44:08]

He has explained it at least twice on record: on the 2021 Starbase tour [SB1 13:29 to 26:26] and to Lex
Fridman in 2024 [LEX438 00:44:08 to 00:48:09]. The steps and their order are the same both times. The order is
the point.

## Step 1 · Make the requirements less dumb

> "First question the requirements, make the requirements less dumb. The requirements are always dumb to some
> degree." [LEX438 00:44:08]

> "It does not matter who gave them to you. It's particularly dangerous, if a smart person gave you the
> requirements, because you might not question them enough." [SB1 13:40]

**Every requirement needs a name:** "it must come with a name, not a department. 'Cause you can't ask the
departments, you have to ask a person." [SB1 16:00] Otherwise, he says, you may be obeying a requirement that an
intern came up with two years ago [SB1 16:16].

## Step 2 · Delete the part or process step

> "If you're not forced to put back at least 10% of what you delete, you're not deleting enough."
> [LEX438 00:44:53]

He says the bias runs "very strongly towards, let's add this part of the process step in case we need it"
[SB1 14:07], so you have to overcorrect, which he calls "a cortical override to a limbic instinct"
[LEX438 00:47:21]. His shortest version: "Best part is no part"
[X 2025-08-13](https://x.com/elonmusk/status/1955735069659947392). Six days later he used the same words about
AI-written code, quoting a post that praised a model for writing only what was asked: "Best part is no part
@Grok" [X 2025-08-19](https://x.com/elonmusk/status/1957619120481984827).

Two deletions from Tesla's AI work, in his posts:
- **A sensor.** "When radar and vision disagree, which one do you believe? Vision has much more precision, so
  better to double down on vision than do sensor fusion." [X 2021-04-10](https://x.com/elonmusk/status/1380796939151704071)
- **Code.** Training vehicle control end to end, he wrote in 2023, "will drop >300k lines of C++ control code by
  ~2 orders of magnitude" [X 2023-08-01](https://x.com/elonmusk/status/1686513363495346178).

**Our reading:** in software the part you delete is often a data source, an integration or a block of code.
His radar question is a usable test: when two inputs disagree and you always trust one, the other may be a part
you don't need.

## Step 3 · Simplify or optimize

> "I'd say the most common mistake of smart engineers is to optimize a thing that should not exist."
> [LEX438 00:44:53]

Why smart people do it: school trains "convergent logic", so "you can't tell a professor, your question is
dumb." [SB1 17:40 to 17:50]

His dated example of simplifying what survived is Raptor 3: "The amount of work required to simplify the Raptor
engine, internalize secondary flow paths and add regenerative cooling for exposed components was staggering." The
payoff, he wrote, was an engine that "doesn't require any heat shield, eliminating heat shield mass & complexity,
as well as the fire suppression system" [X 2024-08-03](https://x.com/elonmusk/status/1819597689283121225).
**Our reading:** good simplification can delete whole subsystems downstream, and it can be the hardest work on
the project, not the easiest.

## Step 4 · Accelerate cycle time

> "However fast you think it can be done, whatever the speed it's being done, it can be done faster. But you
> shouldn't speed things up until you've tried to delete it and optimize." [LEX438 00:47:50]

## Step 5 · Automate

> "I've gone backwards so many times where I've automated something, sped it up, simplified it, and then deleted
> it. And I got tired of doing that." [LEX438 00:48:09]

He said it publicly in the middle of the Model 3 ramp in 2018: "Yes, excessive automation at Tesla was a mistake.
To be precise, my mistake. Humans are underrated."
[X 2018-04-13](https://x.com/elonmusk/status/984882630947753984)

## The story: Model 3 fiberglass mats [SB1 22:21 to 24:42]

In his telling (paraphrased from the caption track): the Model 3 battery pack had fiberglass mats placed by a
robot cell. He worked the steps backwards, speeding up and automating the cell before asking what the mats were
for. The battery team said noise and vibration; the noise team said fire safety. Cars tested with and without
the mats showed no difference, so the mats were deleted, along with "this $2 million robot cell".

A related rule from the same walk-through: production lines often keep end-of-line tests after the problem they
were added for has been diagnosed. Remove them [SB1 25:13].

---

## How to apply it (our suggestion)

Run it in one sitting, on one process, with the people who do the work.

1. **Pick one process** and write its current cost and cycle time at the top.
2. **List every requirement.** For each, write the name of the person who set it. If nobody knows, mark it
   *orphan*. Ask the named person if it's still needed.
3. **Delete,** starting with orphans and "in case we need it" steps. Keep a list of what you deleted.
4. **Simplify** only what survived.
5. **Time the cycle** and make it faster.
6. **Automate** only what is left, and only now.
7. **Set a put-back date** two to four weeks out. If you put back nothing, you didn't delete enough.

### Worked scenario (fictional)

An eight-person agency publishes client reports through 14 steps, taking 9 working days.

| Step of the algorithm | What happened | Steps left | Days |
|---|---|---|---|
| Start | 14 steps, 3 approvals | 14 | 9 |
| 1 · Requirements | 5 requirements had no name. Two approvals traced to one client who left in 2023 | 14 | 9 |
| 2 · Delete | Cut 7 steps, including both orphan approvals and a "final format check" | 7 | 5 |
| 3 · Simplify | Merged two data pulls into one template | 6 | 4 |
| 4 · Accelerate | Ran the data pull overnight instead of on request | 6 | 2 |
| 5 · Automate | Automated the chart export, the only repetitive step left | 6 | 1.5 |
| Put-back review | Put back 1 of 7 (a spell check), about 14% | 7 | 1.5 |

Had they automated first, they would have automated two approvals nobody needed.

### Failure modes

- **Starting at step 5.** Buying automation for a process you haven't questioned. His own mats story is this.
- **Departments as owners.** "Legal wants it" can't be questioned. A named lawyer can.
- **Deleting with no put-back list.** You lose the evidence you need to learn what was actually needed.
- **Never putting anything back.** By his rule, that means you stopped too early.

### Limits

Deleting steps in a safety-critical, regulated or customer-money process is a Dragon change (chapter 05):
delete on paper first, then test, then roll out. His 10% is a rule of thumb for how hard to push, not a
measured constant.

**Use it now:** `templates/01-the-algorithm.md`.

**Checks to run:**
1. List every requirement on the thing you're building. Does each have a person's name on it?
2. What would you delete if you had to put back only one in ten?
3. Is anyone currently automating or speeding up a step nobody has tried to delete?
