---
name: elon-musk-first-principles-playbook
description: Run Elon Musk's engineering method on a product, process, cost or plan, using only his own words (TED talks, Lex Fridman interviews, the Starbase tour, the Tesla master plans he signed, and his posts), with every point cited. Use when someone wants to cut cost or complexity, simplify a product or process, speed up shipping, find the bottleneck, decide how fast to iterate, sequence a company plan, or asks "what would Elon do". Triggers on "first principles", "the algorithm", "delete the part", "best part is no part", "question the requirements", "cost per unit", "cost floor", "idiot index", "limiting factor", "bottleneck", "production hell", "iterate faster", "secret master plan", "what would Elon do".
---

# Elon Musk's First-Principles Playbook

An unofficial, sourced method for attacking a product, a process or a cost the way Elon Musk describes doing
it at SpaceX and Tesla. Built only from his own recorded words. Who he is, for this playbook:
`references/00-who-is-elon-musk.md`.

> "I have this very basic first principles algorithm that I run kind of as a mantra." [LEX438 00:44:08]

## Ground rules for the agent

- Every point cites a source ID (e.g. `[SB1 13:40]`, `[MP1]`, see `SOURCES.md`) or a dated post. **Never put
  words in his mouth.** If the playbook doesn't cover something, say so.
- Quote him briefly and exactly. Paraphrases and software translations are labelled as yours ("our reading").
- The Starbase captions contain mishearings, marked `[sic]`. Don't "fix" a quote silently.
- **Not covered:** his politics, personal life and disputes. Decline to use this skill for those.
- He calls himself "pathologically optimistic on schedule" [LEX400 01:54:38]. Borrow his urgency, not his
  dates. Every deadline you propose should be one the team could actually hit.
- His methods come from rockets and cars. Say so when you translate them to software, services or a small
  team, and keep the translation honest.

---

## Step 1: Get the facts (ask only what you can't see)

1. What are you making, and what is the one goal? Phrase it as "fastest time to...". [SB3 16:42]
2. The product, process or plan you want to attack.
3. Unit economics: price, cost per unit or cost to serve, and the main inputs. [SB1 06:20]
4. What's slow or expensive right now? What's the bottleneck in your view?
5. Team size and who owns which part. [SB1 16:00]
6. What happens when something you ship fails? Who gets hurt? [SB2 05:35]

## Step 2: Find the limiting factor first

Before running anything else, name the **one** thing limiting progress. → `06-the-limiting-factor.md`
Then pick the chapters that fit:

| If the problem is... | Run | Chapter |
|---|---|---|
| Too many steps, parts, features or approvals | The algorithm | `02-the-algorithm.md` |
| Cost too high, margins thin | Cost floor | `04-cost-from-first-principles.md` |
| Thinking by analogy, "that's how it's done" | First principles | `01-first-principles.md` |
| Production, delivery or ops, not the design | The factory | `03-the-factory-is-the-product.md` |
| Shipping too slowly, or breaking things that matter | Iteration mode | `05-iteration-risk-and-speed.md` |
| Unclear what to build in what order | Master plan | `07-strategy-and-sequencing.md` |
| Ownership, communication, hiring | People | `08-people-and-teams.md` |
| Unsure what's true, decision quality | Truth | `09-truth-and-decisions.md` |

## Step 3: Run the algorithm, in order

The five steps, never reordered [SB1 13:29 to 26:26, LEX438 00:44:08 to 00:48:09]:

1. **Make the requirements less dumb.** Each one needs a person's name, not a department. [SB1 16:00]
2. **Delete the part or process step.** If you don't add back about 10%, you didn't delete enough.
   [LEX438 00:44:53]
3. **Simplify or optimize** what's left. Never optimize a thing that should not exist.
4. **Accelerate cycle time.** [LEX438 00:47:50]
5. **Automate**, last. [LEX438 00:48:09]

Push back on the founder if they jump to steps 4 or 5. He has "personally made the mistake of going backwards
on all five steps multiple times." [SB1 22:02]

## Step 4: Deliver the session notes

```markdown
# First-principles session: [company / thing]

**The goal:** fastest time to [X] · **The limiting factor now:** [one line]

## Requirements, each with a name
| Requirement | Name on it | Keep / change / drop |

## Delete
- [Parts/steps deleted] · expected to add back: [~10%]

## Simplify, accelerate, automate (only what survived)
- ...

## Cost floor
- Cost per unit now: ___ · floor from raw inputs: ___ · ratio: ___ · first lever: ___

## Iteration mode
| Thing | Should be Dragon / Falcon / Starship | Is |

## This week
1. [Action] · owner · [source]
2. ...
3. ...

**The number:** [one metric, with today's value and target]

## Where to be careful
- [Schedule realism, safety, regulated or customer-facing parts]
```

Rules for the notes:
- **At most three actions**, each with a person's name.
- **One number.** His version is "cost per ton to orbit". [SB1 06:20]
- **Mark every translation** from hardware to the founder's world as our reading.

Templates for the founder: `templates/01-the-algorithm.md`, `templates/02-cost-floor.md`,
`templates/03-limiting-factor-log.md`, `templates/04-iteration-mode.md`, `templates/05-secret-master-plan.md`.
A full example: `examples/01-worked-session.md`.
