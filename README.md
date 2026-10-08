# Elon Musk's First-Principles Playbook

**An unofficial, fully sourced playbook and AI skill that runs Elon Musk's engineering method (first
principles, the five-step algorithm, the cost floor, the limiting factor) on your product, process or plan.
Built only from his own recorded words.**

Elon Musk runs SpaceX and Tesla, and co-founded Neuralink and xAI. He has explained how he attacks cost,
complexity and speed many times on the record: at TED, to Lex Fridman and Dwarkesh Patel, walking through the
Starbase rocket factory, at the 2017 International Astronautical Congress, in the Tesla master plans and blog
posts he signed, and in his own posts on X. This repo turns those into a method you can run on your own company
this week.

> "I'd say the most common mistake of smart engineers is to optimize a thing that should not exist."
> Elon Musk, Lex Fridman Podcast #438 (2024) [LEX438 00:44:53]

> ⚠️ **Unofficial.** Not written, reviewed or endorsed by Elon Musk or any of his companies. It's a structured
> guide in our own words, with short credited quotes and a link to every source. It covers his methods for
> building things only: no politics, no personal life.

---

## What's inside

### The playbook

| # | Chapter | What you'll learn |
|---|---|---|
| 00 | [Who he is, for this playbook](references/00-who-is-elon-musk.md) | Scope, sources, and his own caveats |
| 01 | [First principles](references/01-first-principles.md) | Reason up from truths, not analogy · think in the limit · reality is the judge |
| 02 | [The algorithm](references/02-the-algorithm.md) | Question requirements · delete · simplify · accelerate · automate, in that order |
| 03 | [The factory is the product](references/03-the-factory-is-the-product.md) | Production is the hard part · Model 3 production hell · ramps follow an S-curve · be on the line |
| 04 | [Cost from first principles](references/04-cost-from-first-principles.md) | The material floor · steel vs carbon fiber · one number · 10x targets · complete reuse |
| 05 | [Iteration, risk and speed](references/05-iteration-risk-and-speed.md) | Dragon, Falcon, Starship modes · 50th-percentile deadlines · when to act drastically |
| 06 | [The limiting factor](references/06-the-limiting-factor.md) | Find the one constraint · it moves (line, heat shield, turbines) · spend your time there |
| 07 | [Strategy and sequencing](references/07-strategy-and-sequencing.md) | The secret master plan · make your own products redundant · open patents · orbit before doors |
| 08 | [People, hiring and reviews](references/08-people-and-teams.md) | Evidence of exceptional ability · everyone is chief engineer · skip-level weekly reviews |
| 09 | [Truth and decisions](references/09-truth-and-decisions.md) | A decision method: foundations first · weigh by value · agreement across disagreement |
| 10 | [Make it yourself](references/10-make-it-yourself.md) | When to build a part instead of buying it · the steel Starship · supplier bottlenecks |

Every chapter now ends with a "how to apply" section in our words: steps, a fictional worked scenario with
numbers, failure modes and limits.

### Templates

| Template | Use it to |
|---|---|
| [01 The algorithm](templates/01-the-algorithm.md) | Run the five steps, in order, on one process or product |
| [02 Cost floor](templates/02-cost-floor.md) | Compare your unit cost with the raw inputs, and set a 10x target |
| [03 Limiting factor log](templates/03-limiting-factor-log.md) | Name the one constraint every week, and who's on it |
| [04 Iteration mode](templates/04-iteration-mode.md) | Decide what's a Dragon, a Falcon or a Starship, and ship at that speed |
| [05 Secret master plan](templates/05-secret-master-plan.md) | Write your strategy as four lines, each funding the next |
| [06 Engineering review](templates/06-engineering-review.md) | Run a weekly skip-level review on the limiting factor, and plot the trend |
| [07 Hiring scorecard](templates/07-hiring-scorecard.md) | Hire for evidence of exceptional ability, talent, drive and trustworthiness |
| [08 Decision check](templates/08-decision-check.md) | Test a decision's foundations, put odds on it and log it |

### Worked example

[A full session, start to finish](examples/01-worked-session.md): a fictional SaaS startup with invented
numbers, run through the whole skill. The skill asks for the numbers it needs and the founder supplies them.
Onboarding went from 11 steps to 4.

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
- *What would I delete from this product if I had to add back only 10%?*
- *What's our cost floor, and what's the 10x lever?*
- *What's the limiting factor in our company right now?*
- *Are we iterating too slowly on this, or too fast on that?*
- *Write our secret master plan in four lines.*
- *Question the requirements on this spec.*
- *Should we build this part ourselves or keep buying it?*
- *Set up a weekly review for our bottleneck.*

### 2. Use the templates (30 minutes, no AI)

1. [The algorithm](templates/01-the-algorithm.md) on your slowest process.
2. [Cost floor](templates/02-cost-floor.md) once a quarter.
3. [Limiting factor log](templates/03-limiting-factor-log.md) every week.
4. [Iteration mode](templates/04-iteration-mode.md) when shipping feels too slow or too risky.
5. [Secret master plan](templates/05-secret-master-plan.md) once a year, or before a raise.
6. [Engineering review](templates/06-engineering-review.md) every week, on the limiting factor.
7. [Hiring scorecard](templates/07-hiring-scorecard.md) for every hire.
8. [Decision check](templates/08-decision-check.md) for any decision worth more than a day.

### 3. Read it

Start with chapter 02 if you have one process to fix today, 04 if margins are the problem, 06 if you don't
know what's blocking you, 07 if you're deciding what to build next, 08 if you're hiring, and 10 if a supplier is holding you back.

**His own caveat:** "I would say that I'm pathologically optimistic on schedule." [LEX400 01:54:38] Take the urgency, not the
dates.

---

## How it stays honest

- **First-party only:** his talks, interviews, papers, his posts on X and the Tesla posts he signed. No
  biographies, no listicles of *Musk's rules*.
- **Quotes checked by script against saved copies of their sources:** official transcripts, archived posts and
  PDFs, and for Starbase the YouTube auto-caption tracks (excerpts for Parts 1 and 2). A Starbase quote matches
  the captions, which may not match what he said. Details in [`SOURCES.md`](SOURCES.md#how-quotes-were-checked).
- **Short quotes:** none over about 60 words; trims marked with an ellipsis; long posts on X quoted for two
  sentences at most.
- **Every claim cited** with a source ID and timestamp, which map to links in [`SOURCES.md`](SOURCES.md).
- **Caption errors flagged:** the Starbase videos have auto-captions; mishearings are marked `[sic]`.
- **Famous but unverified phrases left out:** "idiot index" isn't in these sources, so it isn't quoted.
- **Company-authored text isn't his:** Tesla's 2023 and 2025 master plans are signed by The Tesla Team and
  aren't quoted as his words.
- **Our own reading is marked**, never presented as his words.

## Sources

The full list, with dates, links and timestamps, is in [`SOURCES.md`](SOURCES.md):

TED 2013, 2017 and 2022 (with Chris Anderson) · Lex Fridman Podcast #49 (2019), #400 (2023) and #438 (2024) ·
Dwarkesh Podcast (2026) · Starbase Tour with Elon Musk, Parts 1 to 3 (Everyday Astronaut, 2021) · IAC 2017
"Making Life Multiplanetary" (SpaceX abridged transcript) · "Making Humans a Multi-Planetary Species", New
Space (2017) · Hyperloop Alpha (2013, opening section) · The Secret Tesla Motors Master Plan (2006) · The
Mission of Tesla (2013) · All Our Patent Are Belong To You (2014) · Master Plan, Part Deux (2016) · 51 posts on X
(2013 to 2026). 17 sources, plus the posts.

## What's new in v2

- Fixes from an independent audit: a mislabelled Neuralink quote, a host's metaphor removed, context added,
  dead links replaced with archive copies, TED timestamps added, skill paths fixed.
- Six new first-party sources, covering hiring, reviews, deadlines, the steel Starship, open patents, funding
  the next rocket and the 2026 power bottleneck.
- Chapter 10 (make it yourself) and templates 06 to 08.
- 44 more of his posts on X (51 in all), each dated from its ID: production hell as it happened, Raptor cost
  targets, the booster catch, test-flight reviews, the limiting factor moving in self-driving, and his hiring posts.
- Every chapter has a method section in our words. Fewer, shorter quotes.

## License

- **Our text** (chapters, skill, templates, structure): [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
- **Quotes** remain Elon Musk's words and their publishers'. They're short, credited excerpts for commentary
  and are **not** covered by this license.

See [`LICENSE`](LICENSE).

## Corrections

Spot a misquote or a broken link? Open an issue with the source and timestamp.
