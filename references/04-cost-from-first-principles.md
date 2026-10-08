# 04 · Cost from first principles

## Find the floor: what do the inputs actually cost?

His rocket example:

> "So the cost of the propellant is about .3 percent of the cost of the rocket. So it's possible to achieve,
> let's say, roughly 100-fold improvement in the cost of spaceflight if you can effectively reuse the rocket."
> [TED13 15:11]

And the general rule, from 2026:

> "When you do volume production, you can get any given thing to start to approach its material cost."
> [DW 01:44:16]

**The move:** compare the price of a thing with the cost of what it's physically made of. A big gap means
most of the cost is in how it's made, which is where first principles can cut. (A widely repeated name for this
ratio is the "idiot index". We could not find it in the first-party sources used here, so this playbook doesn't
quote it.)

## Choose the material by its floor

The steel Starship is his clearest case [DW 01:44:16]. In 2016 the ship was planned in "advanced carbon fiber"
[NS17]. By his 2026 account, the carbon fiber that can hold cryogenic oxygen costs "roughly 50 times the cost of
steel", and the team was struggling to make even a small barrel section without wrinkles. Stainless steel looked
twice as heavy at room temperature but, at cryogenic temperature, comes close to carbon fiber on
strength-to-weight, and "it costs 50x less in raw material and is very easy to work with". It also needs less
heat shield, so he says the steel rocket ended up lighter. His verdict: "It was dumb not to do steel."
[DW 01:44:16]

**Our reading:** the material's floor price beat its catalogue reputation. Nobody would pick steel to save
weight, until the whole system was counted.

## Name the one number that matters

> "The fundamental thing that needs to be fixed is the cost per ton to orbit. So things that address the cost
> per ton to orbit are good." [SB1 06:20 to 06:26]

For Raptor, the sub-number was getting the cost per ton of thrust under a thousand dollars [SB1 06:10 to 06:16].
For Mars, he set the gap as a multiple: the cost of trips had to improve "by five million percent", about four
and a half orders of magnitude [NS17].

## Set the target as a multiple, then find the lever

> "I think we need to have at least a tenfold improvement in the cost per mile of tunneling." [TED17 02:59]

His first lever was to "cut the tunnel diameter by a factor of two or more" [TED17 03:36]. For cars, the 2016
plan said first-principles analysis of production suggested a 5 to 10 fold improvement was achievable by version
3 [MP2].

**Our reading:** he sets the multiple from the floor, not from last year's cost. Then he looks for the one
physical change (diameter, material, reuse) that moves it most.

## Reuse only counts if it's complete

> "So it's important to appreciate that reusability is only relevant if it is rapid and complete." [TED17 31:24]

His aircraft comparison: chartering a fully reusable 747 costs about a third as much as buying a tiny expendable
aircraft for the same trip, because one you build each time and the other you only refuel [IAC17].

## Mass, and where you put it

> "So, every one ton of mass begets an extra ton." [SB2 24:08]

"If you can move mass to the ground side, it's better to move mass to the ground side." [SB2 30:24] He applies it: that's why the booster has no legs and the tower
catches it [SB2 30:28]. Hyperloop used the same logic in reverse: put the complexity in the pod, because "it is
important to make the tube as low cost and simple as possible" [HYP13].

---

## How to apply it (our suggestion)

1. **Name your cost per ton to orbit**: the one unit cost that decides whether you win.
2. **Break it into raw inputs.** Price each one at what you'd pay at volume.
3. **Compute the ratio**: current cost divided by the floor.
4. **Sort the gap** into process, waste, one-off use and overhead.
5. **Pick a multiple** (5x, 10x) and the single change that moves it most: a material, a reuse, a deletion, a
   move to the ground side.
6. **Recount the whole system** before you choose. The steel lesson: a part that is worse alone can make the
   system cheaper and better.

### Worked scenario (fictional)

A company sells a smart water meter for $180. Cost to build: $96.

| Input | Cost at volume |
|---|---|
| Electronics (board, chips, radio) | $14 |
| Machined brass body | $22 |
| Battery | $3 |
| Assembly and test labour | $31 |
| Packaging, freight, rework | $26 |
| **Raw-input floor** (electronics, brass, battery) | **$39** |

Ratio: $96 ÷ $39 ≈ 2.5. The gap is labour and rework, not parts. Lever 1: a moulded composite body replaces
machined brass ($22 to $6) and removes four assembly steps. Lever 2 (ground side): move calibration from each
meter into the cloud software, cutting test time by two thirds. New cost about $55, close to a 2x cut, which
makes a $99 retail price possible for a market three times the size.

### Failure modes

- **Measuring the floor at prototype prices.** His claim is about volume production.
- **Comparing parts, not systems.** Carbon fiber looked lighter part by part; steel won on the whole ship.
- **Reuse that isn't complete.** If each reuse needs a slow, manual refurbish, it may not pay.
- **One number that isn't the one.** A cost per unit nobody buys on is the wrong number.

### Limits

In software, the floor (compute, storage, human minutes) is often far below price, and the price reflects
value, not cost. The cost floor tells you how low you could go, not what you should charge. The 2026 steel
account is his retelling years after the decision; he jokes in the same passage that critics will dispute his
numbers [DW 01:44:16].

**Use it now:** `templates/02-cost-floor.md`. For whether to make a part yourself, see chapter 10.

**Checks to run:**
1. What is your cost per ton to orbit?
2. What do the raw inputs cost, and how far is your cost from that floor?
3. What 10x target would change the business, and what's the first lever?
4. What could you move to the ground side: out of each unit, into infrastructure you don't ship each time?
