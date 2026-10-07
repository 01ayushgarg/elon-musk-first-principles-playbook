# 04 · Cost from first principles

## Find the floor: what do the inputs actually cost?

His rocket example:

> "So the cost of the propellant is about .3 percent of the cost of the rocket. So it's possible to achieve,
> let's say, roughly 100-fold improvement in the cost of spaceflight if you can effectively reuse the rocket."
> [TED13]

**The move:** compare the price of a thing with the cost of what it's physically made of (or, in software,
the raw cost to deliver it). A big gap means most of the cost is in how it's made, which is where first
principles can cut. (A widely repeated name for this ratio is the "idiot index". We could not find it in the
first-party transcripts used here, so this playbook doesn't quote it.)

## Name the one number that matters

> "The fundamental thing that needs to be fixed is the cost per ton to orbit. So things that address the cost per
> ton to orbit are good." [SB1 06:20 to 06:26]

> "What is super hard about Raptor is, how do we make a Raptor where the cost per ton of thrust is under a
> thousand dollars?" [SB1 06:10 to 06:16]

> "At it's heart, it is a fundamentally an optimization of cost per ton to orbit and then ultimately cost per
> ton to the surface of Mars." [SB1 06:45 to 06:54]

## Set the target as a multiple, then find the lever

> "I think we need to have at least a tenfold improvement in the cost per mile of tunneling." [TED17]

> "So the first thing to do is to cut the tunnel diameter by a factor of two or more." [TED17]

> "A first principles physics analysis of automotive production suggests that somewhere between a 5 to 10 fold
> improvement is achievable by version 3 on a roughly 2 year iteration cycle." [MP2]

## Reuse only counts if it's complete

> "So it's important to appreciate that reusability is only relevant if it is rapid and complete." [TED17]

## Mass, and where you put it

> "So, every one ton of mass begets an extra ton." [SB2 24:08]

> "If you can move mass to the ground side, it's better to move mass to the ground side." [SB2 30:24] "That's why
> we took the legs off the booster and just have the tower catch it." [SB2 30:28]

## Redesign the input, not just the product

> "Tesla engineering redesigned lithium refining from physics first principles"
> [X 2026-04-18](https://x.com/elonmusk/status/2045309037848272993)

**Applying it** (our reading): in software, the "propellant" is compute, storage and the minutes of human work
per customer. Compare your price, and your cost to serve, with that floor.

**Use it now:** `templates/02-cost-floor.md`.

**Checks to run:**
1. What is your "cost per ton to orbit": the single unit cost that decides whether you win?
2. What do the raw inputs cost, and how far is your price from that floor?
3. What 10x target would change the business, and what's the first lever (like halving the tunnel diameter)?
4. What could you move "to the ground side": out of the product, into infrastructure you don't ship each time?
