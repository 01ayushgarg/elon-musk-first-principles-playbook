# 03 · The factory is the product

## Production is the hard part

> "I think, currently a factory is underrated and design is overrated." [SB1 03:49]

He puts the effort ratio at "10 to a 100 times more effort to design the manufacturing system than the engine"
[SB1 04:24], and says people who haven't worked in manufacturing think "production is like a copier or something
like that. This is completely false." [SB1 05:03 to 05:15]

> "So the hard part is not creating a prototype or going into limited production. The absolutely difficult
> thing, which has not been accomplished by an American car company in 100 years, is reaching volume
> production without going bankrupt." [TED22 32:42]

## The machine that makes the machine

> "That is why Tesla engineering has transitioned to focus heavily on designing the machine that makes the
> machine -- turning the factory itself into a product." [MP2]

The reason he gives in the same plan: what matters for the mission is scaling production volume "as quickly as
possible" [MP2].

## Production hell: the Model 3 line

His own account, at TED in 2022:

> "So we basically messed up almost every aspect of the Model 3 production line, from cells to packs to drive
> inverters, motors, body line, the paint shop, final assembly, everything." [TED22 33:46]

He rejects the idea that doing more by hand would simply have fixed it [TED22 33:46], and says he lived in the
Fremont and Nevada factories for three years fixing the line, sleeping on the floor so the team could see he was
there [TED22 33:46]. In September 2018 he posted that Tesla had gone "from production hell to delivery logistics
hell", which he called "far more tractable"
[X 2018-09-17](https://x.com/elonmusk/status/1041500594467270656). **Our reading:** the limiting factor moved
from the line to the trucks, and he said so publicly the moment it did (chapter 06).

## Ramps follow an S-curve

> "The output per unit time always follows an S-curve. It starts off agonizingly slow, then it has this
> exponential increase, then a linear, then a logarithmic outcome until you eventually asymptote at some
> number." [DW 01:17:21]

He adds that a product with all-custom parts and no existing supply chain will "initially ramp slower" than one
built from catalogue parts [DW 01:17:21].

## Be on the line

> "Whatever the people at the front lines are doing, I try to do it at least a few times myself."
> [LEX438 00:50:52]

Two simplifications he made to the product to make the line easier: taking two of seven Tesla paint colours
off the standard menu in 2018 [X 2018-09-11](https://x.com/elonmusk/status/1039390759907020801), and designing
the Optimus robot "to be manufactured in the same way they would make a car" [LEX400 02:11:02]. He calls the
mismatch between steady factories and seasonal demand "the essential quandary of manufacturing"
[X 2024-02-11](https://x.com/elonmusk/status/1756751879701156059).

---

## How to apply it (our reading)

In software or services, "the factory" is the system that produces the product every day: onboarding,
delivery, support, the content pipeline, the release process. These steps are our suggestion.

1. **Draw the line.** Write every station a unit of work passes through, from order to delivered, with the time
   spent at each and the time spent waiting between them.
2. **Find the station with the queue.** That is the limiting factor (chapter 06).
3. **Do that station's work yourself,** at least a few times, before changing it.
4. **Cut variants.** Every option on the menu is a branch on the line. Which ones could move to "special
   request"?
5. **Plot the ramp** weekly: units out per week. Expect the S-curve. Judge progress by the slope, not by
   one week.
6. **Give the factory an owner** with a name, a design document and a metric, like any product.

### Worked scenario (fictional)

A meal-kit startup ships 1,200 boxes a week and wants 5,000 by the end of the quarter.

| Station | Minutes per box | Queue at peak |
|---|---|---|
| Picking | 4 | Small |
| Packing | 3 | Small |
| Cold-chain labelling | 6 | 300 boxes |
| Dispatch | 1 | None |

Labelling is the line's limit. The founder works the labelling bench for two shifts and finds that 9 of the
21 recipes need a unique label. Cutting the menu to 12 recipes and moving 3 more to "pre-order only" removes 70%
of label changes. Output hits 2,000 in three weeks, slowly at first, then faster: the S-curve. The next queue
appears at dispatch, as the post-2018 Tesla example would predict.

### Failure modes

- **Treating launch as the finish.** The prototype is the easy part, by his account.
- **Automating a messy line.** His Model 3 lesson is that the line itself was wrong, station by station.
- **Managing the ramp from a dashboard.** He went to the line. A dashboard shows where the queue is, not why.
- **Expecting a straight line.** An S-curve looks like failure for the first weeks.

### Limits

His ramps are factories of thousands of people and billions of dollars. In a small team the "line" may be one
person's week. The principle (design the system that makes the product) scales down; the numbers don't.
For when to build your own parts instead of buying them, see chapter 10.

**Checks to run:**
1. What's your "factory"? Who owns its design?
2. How much effort goes into the thing, and how much into the system that produces it?
3. When did you last do the front-line work yourself?
4. Which options or variants could you cut to simplify production?
