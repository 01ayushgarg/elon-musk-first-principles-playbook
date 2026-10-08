# 05 · Iteration, risk and speed

## Match how much you iterate to the cost of failure

He describes three modes at SpaceX [SB2 05:35 to 06:22]:

| Mode | In his words |
|---|---|
| Dragon (crew) | "Dragon, there can be no failures ever." "That's extreme conservatism." |
| Falcon | "Then Falcon is a little less conservative." |
| Starship | "We're iterating rapidly in order to create the first ever fully reusable rocket." |

Starship can iterate fast because nobody is on board, so "we can blow things up" [SB2 08:33].

## Fear of change is a risk too

> "There was a risk/reward asymmetry. So, big punishment for, if you make a change and something goes wrong,
> big punishment. If you make a change and it goes right, small reward." [SB2 07:34]

On the Space Shuttle, he says, "a lack of iteration was the problem": people knew about issues but "were too
afraid to make change" [SB2 07:19]. "It worked before" is not evidence; his comparison is Russian roulette
[SB2 08:07].

## Push the envelope, knowing the cost

> "And frankly, if you don't push the envelope, you cannot achieve the goal of a fully and rapidly reusable
> rocket." [SB2 23:02]

He admits what that costs. None of the causes of Starship's early explosions were on the risk list
[SB1 33:04]. In 2026 he described Raptor 3 as an engine that "desperately wants to blow up", with "thousands of
ways that it could explode and only one way that it doesn't" [DW 01:44:16].

## Judge a test flight by what it taught

His posts around Starship test flights follow one pattern: odds before, data after.
- **Before.** Asked in November 2020 how he rated the chances of the next Starship prototype landing in one
  piece: "Lot of things need to go right, so maybe 1/3 chance"
  [X 2020-11-25](https://x.com/elonmusk/status/1331388984023461888).
- **After.** The landing ended in an RUD (rapid unscheduled disassembly). His summary: "Fuel header tank pressure was low during landing burn, causing
  touchdown velocity to be high & RUD, but we got all the data we needed!"
  [X 2020-12-09](https://x.com/elonmusk/status/1336809767574982658)
- **One goal per flight.** Before Flight 4 in 2024: "Primary goal is getting through max reentry heating."
  [X 2024-05-20](https://x.com/elonmusk/status/1792629142141177890)
- **Progress, failure, cadence.** After a 2025 flight he listed what improved, what failed ("Leaks caused loss of
  main tank pressure during the coast and re-entry phase"), then "Lot of good data to review" and a faster
  cadence of "approximately 1 every 3 to 4 weeks" [X 2025-05-28](https://x.com/elonmusk/status/1927531406017601915).

**Our reading:** for Starship-mode work, write the odds and the one goal down before the test, and report the
result against them after. A failed test that hit its learning goal is a result; a test with no stated goal
teaches nothing you can check.

## Make it work, then make it efficient

> "In general, with any given technology, you first try to make it work, and then you make it efficient."
> [LEX400 02:07:56]

Early production is for learning: "All of the initial production is simply a learning exercise... what
knowledge can you learn in the shortest period of time?" [SB3 17:09] He compares good iteration to a guided
missile that keeps correcting its course, against a precise cannon ball fired before you know where the target
is [SB3 16:27 to 16:33].

When customers depend on the product, he moved the risky learning elsewhere. Falcon 9 didn't have Starship's
freedom, but "Technically we did have the Grasshopper program." [SB3 17:49]

He iterates the factory along with the design: "Successive iteration of both design & manufacturing. Latter is
1000% harder than former." [X 2020-04-26](https://x.com/elonmusk/status/1254443441469128704) And he will
replace a design that works: "Raptor 2 has significant improvements in every way, but a complete design overhaul
is necessary for the engine that can actually make life multiplanetary."
[X 2021-11-17](https://x.com/elonmusk/status/1460813037670219778) For Tesla's AI chips he set the iteration as
a fixed cadence: "Our goal is to bring a new AI chip design to volume production every 12 months."
[X 2025-11-23](https://x.com/elonmusk/status/1992499020590108745) **Our reading:** a fixed cadence turns
iteration from a hope into a schedule you can review.

## Deadlines: aggressive, but at the 50th percentile

> "So it's not like an impossible deadline, but it's the most aggressive deadline I can think of that could be
> achieved with 50% probability. Which means that it'll be late half the time." [DW 01:44:16]

He gives the reason as "a law of gas expansion that applies to schedules": a five-year deadline "will expand to
fill the available schedule" [DW 01:44:16]. He also names the limit on speed: "Physics will limit how fast you
can do certain things." [DW 01:44:16]

**Our reading:** this explains his public lateness. A deadline set at a coin-flip will be missed about half the
time by design. Borrow the method, not the dates. He calls himself "pathologically optimistic on schedule"
[LEX400 01:54:38].

## Urgency

> "Generally, a maniacal sense of urgency is a very big deal. You want to have an aggressive schedule and you want
> to figure out what the limiting factor is at any point in time and help the team address that limiting
> factor." [DW 01:44:16]

At Starbase he put it as odds: with extreme urgency there's a chance of making life multi-planetary; without it
"that chance is probably zero" [SB3 13:10]. On time: "Time is the true currency." [LEX438 01:18:28]

## When to take drastic action

> "I'll take drastic action only when I conclude that success is not in a set of possible outcomes." [DW 01:44:16]

His test is a trend, not a moment: with weekly reviews you can "mentally plot the points on a curve" and ask
whether the work is converging [DW 01:44:16] (chapter 08).

---

## How to apply it (our suggestion)

1. **Sort every piece of work into a mode.** Dragon: failure hurts people, money or trust you can't win back.
   Falcon: failure hurts paying customers but is recoverable. Starship: nobody is on board.
2. **Check the speed matches the mode.** Count reviews and days per change.
3. **Fix the incentives.** If a failed change costs more to the person than a good change earns, people stop
   changing things.
4. **Set each deadline at your honest 50th percentile.** Write down the date you think is a coin-flip, and
   expect to miss half.
5. **Plot progress weekly** on the thing that matters. If the line isn't converging, change course; if success
   has left the set of possible outcomes, act drastically.

### Worked scenario (fictional)

A fintech app has three streams of work.

| Work | Should be | Was | Fix |
|---|---|---|---|
| Card payments | Dragon | Falcon (shipped weekly, no rollback) | Staged rollout, rollback, two reviewers |
| Spending insights screen | Falcon | Dragon (three sign-offs, 3 weeks per change) | One reviewer, feature flag, weekly |
| New budgeting prototype | Starship | Dragon | Opt-in testers, ship daily |

Deadline for the prototype: the team's honest guesses range from 4 to 10 weeks. The 50th percentile is about
6 weeks, so 6 is the deadline, not 4 (wishful) or 10 (gas expansion). Week 3 plot: activation of testers rising
from 8% to 19% to 27%. Converging, so no drastic action.

### Failure modes

- **A Starship run like a Dragon.** Weeks of review for something no customer sees.
- **A Dragon run like a Starship.** "Move fast" applied to payments, health or data.
- **Impossible deadlines.** A 10th-percentile date is not urgency; it teaches people to ignore dates.
- **Drastic action on one bad week.** His test is the curve, not the point.

### Limits

His Starship tolerance comes from having no crew on board and a launch site he controls. Most companies have
customers on every flight. The Grasshopper move (a separate test track) is often the only honest way to get
Starship speed.

**Use it now:** `templates/04-iteration-mode.md`.

**Checks to run:**
1. For each thing you're building: is it a Dragon, a Falcon or a Starship? Is the speed right?
2. Does your culture punish a failed change more than it rewards a good one?
3. Is each deadline your honest 50th percentile?
4. What are you waiting on that you could start in parallel?
