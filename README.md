# Elon Musk's First-Principles Playbook

**An unofficial, fully sourced playbook and AI skill that runs Elon Musk's engineering method (first
principles, the five-step algorithm, the cost floor, the limiting factor) on your product, process or plan.
Built only from his own recorded words.**

Elon Musk runs SpaceX and Tesla, and co-founded Neuralink and xAI. He has explained how he attacks cost,
complexity and speed many times on the record: at TED, to Lex Fridman, walking through the Starbase rocket
factory, and in the two Tesla master plans he signed. This repo turns those into a method you can run on your
own company this week.

> "I'd say the most common mistake of smart engineers is to optimize a thing that should not exist."
> Elon Musk, Lex Fridman Podcast #438 (2024)

> ⚠️ **Unofficial.** Not written, reviewed or endorsed by Elon Musk or any of his companies. It's a structured
> guide in our own words, with short credited quotes and a link to every source. It covers his methods for
> building things only: no politics, no personal life.

---

## What's inside

### The playbook

| # | Chapter | What you'll learn |
|---|---|---|
| 00 | [Who he is, for this playbook](references/00-who-is-elon-musk.md) | Scope, sources, and his own caveats |
| 01 | [First principles](references/01-first-principles.md) | Reason up from truths, not analogy · physics as a tool · think in the limit · be calibrated |
| 02 | [The algorithm](references/02-the-algorithm.md) | Question requirements · delete · simplify · accelerate · automate, in that order |
| 03 | [The factory is the product](references/03-the-factory-is-the-product.md) | Production is the hard part · the machine that makes the machine · be on the line |
| 04 | [Cost from first principles](references/04-cost-from-first-principles.md) | The cost floor · one number that matters · 10x targets · rapid and complete reuse |
| 05 | [Iteration, risk and speed](references/05-iteration-risk-and-speed.md) | Dragon, Falcon, Starship modes · fear of change · urgency · time as currency |
| 06 | [The limiting factor](references/06-the-limiting-factor.md) | Find the one constraint · it moves · go to where it is |
| 07 | [Strategy and sequencing](references/07-strategy-and-sequencing.md) | The secret master plan · nested goals · orbit before doors · the tech tree |
| 08 | [People and teams](references/08-people-and-teams.md) | Everyone is chief engineer · requirements have owners · compressed communication |
| 09 | [Truth and decisions](references/09-truth-and-decisions.md) | Obsessed with truth · foundations first · decisions by percentage |

### Templates

| Template | Use it to |
|---|---|
| [01 The algorithm](templates/01-the-algorithm.md) | Run the five steps, in order, on one process or product |
| [02 Cost floor](templates/02-cost-floor.md) | Compare your unit cost with the raw inputs, and set a 10x target |
| [03 Limiting factor log](templates/03-limiting-factor-log.md) | Name the one constraint every week, and who's on it |
| [04 Iteration mode](templates/04-iteration-mode.md) | Decide what's a Dragon, a Falcon or a Starship, and ship at that speed |
| [05 Secret master plan](templates/05-secret-master-plan.md) | Write your strategy as four lines, each funding the next |

### Worked example

[A full session, start to finish](examples/01-worked-session.md): a fictional SaaS startup with invented
numbers, run through the whole skill. Onboarding went from 11 steps to 4.

---

## How to use this

### 1. Run it as an AI skill (10 minutes)

**Install** into your agent's skills folder. For Claude Code:

```bash
git clone https://github.com/01ayushgarg/elon-musk-first-principles-playbook \
  ~/.claude/skills/elon-musk-first-principles-playbook
```

If your agent doesn't read skill folders, paste `SKILL.md` into the chat and attach the chapters it asks for.

**Then ask it to run the algorithm.** Copy and fill in:

```text
Run Elon Musk's algorithm on my startup.

What we make:
The goal, as "fastest time to...":
The process or product to attack:
Unit economics (price, cost per unit or cost to serve):
Team, and who owns what:
What's slow or expensive right now:
What happens when something we ship breaks:
```

**You get back:** the limiting factor, every requirement with a name on it (or flagged for having none), what
to delete, what's left to simplify, speed up and automate, your cost floor and the gap to it, which iteration
mode each part of your work should be in, three actions for this week and one number to watch. Every point
cites the talk, interview or post it comes from.

**Other things you can ask:**
- *"What would I delete from this product if I had to add back only 10%?"*
- *"What's our cost floor, and what's the 10x lever?"*
- *"What's the limiting factor in our company right now?"*
- *"Are we iterating too slowly on this, or too fast on that?"*
- *"Write our secret master plan in four lines."*
- *"Question the requirements on this spec."*

### 2. Use the templates (30 minutes, no AI)

1. [The algorithm](templates/01-the-algorithm.md) on your slowest process.
2. [Cost floor](templates/02-cost-floor.md) once a quarter.
3. [Limiting factor log](templates/03-limiting-factor-log.md) every week.
4. [Iteration mode](templates/04-iteration-mode.md) when shipping feels too slow or too risky.
5. [Secret master plan](templates/05-secret-master-plan.md) once a year, or before a raise.

### 3. Read it

Start with chapter 02 if you have one process to fix today, 04 if margins are the problem, 06 if you don't
know what's blocking you, and 07 if you're deciding what to build next.

**His own caveat:** "I would say that I'm pathologically optimistic on schedule." Take the urgency, not the
dates.

---

## How it stays honest

- **First-party only:** his talks, interviews, his posts on X and the master plans he signed. No biographies,
  no listicles of "Musk's rules".
- **Every quote checked by script** against the raw transcript or text before publishing.
- **Every claim cited** with a source ID and timestamp, which map to links in [`SOURCES.md`](SOURCES.md).
- **Caption errors flagged:** the Starbase videos have auto-captions; mishearings are marked `[sic]`.
- **Famous but unverified phrases left out:** "idiot index" isn't in these sources, so it isn't quoted.
- **Company-authored text isn't his:** Tesla's 2023 and 2025 master plans are signed by "The Tesla Team" and
  aren't quoted as his words.
- **Our own reading is marked**, never presented as his words.

## Sources

The full list, with dates, links and timestamps, is in [`SOURCES.md`](SOURCES.md):

TED 2013, 2017 and 2022 (with Chris Anderson) · Lex Fridman Podcast #49 (2019), #400 (2023) and #438 (2024) ·
Starbase Tour with Elon Musk, Parts 1 to 3 (Everyday Astronaut, 2021) · The Secret Tesla Motors Master Plan
(2006) · Master Plan, Part Deux (2016) · 7 posts on X (2018 to 2026).

## License

- **Our text** (chapters, skill, templates, structure): [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
- **Quotes** remain Elon Musk's words and their publishers'. They're short, credited excerpts for commentary
  and are **not** covered by this license.

See [`LICENSE`](LICENSE).

## Corrections

Spot a misquote or a broken link? Open an issue with the source and timestamp.
