# 10 · Make it yourself: vertical integration and materials

New in v2. When does he build a part instead of buying it? His sources give a consistent answer: when the part
doesn't exist, when it is the limiting factor, or when its price is far above its material floor.

## When the part doesn't exist

> "I was surprised at the fact that we had to develop every part of the robot ourselves. That there were no off
> the shelf motors, electronics, sensors. We had to develop everything." [LEX400 02:09:47]

By 2026 his description of Optimus was the same: "Everything had to be designed from physics first principles.
There is no supply chain for this." [DW 01:17:21] He adds the cost of that choice: with nothing taken from a
catalogue, production "is going to initially ramp slower than a product where you have an existing supply
chain" [DW 01:17:21].

## When the part is the limiting factor

For power, the bottleneck he names is the cast blades and vanes inside gas turbines, made by "only three casting
companies in the world" that are "massively backlogged" [DW 00:00:00]. His conclusion: "SpaceX and Tesla will
probably have to make the turbine blades, the vanes and blades, internally." [DW 00:00:00]

For solar, asked how far down the stack to go, he said "you've got to do the whole thing from raw materials to
finish the cell" [DW 00:00:00]. In 2026 he also posted that Tesla had redesigned lithium refining from physics
first principles [X 2026-04-18](https://x.com/elonmusk/status/2045309037848272993).

## When the price is far above the material floor

The steel Starship (chapter 04) is the material version of the same choice. Carbon fiber was the catalogue
answer for a light rocket. Counted from raw material, cryogenic behaviour, welding and heat shield, steel won,
and he says "we should have started with steel in the beginning" [DW 01:44:16]. Part of the case was working
conditions: "You can weld stainless steel outdoors." [DW 01:44:16]

Two posts show where the material choice led. In 2019 he said the steel moved between companies: "Starship steel
decision came first. We were going to use titanium skins for Cybertruck, but cold-rolled 30X stainless is much
stronger." [X 2019-11-24](https://x.com/elonmusk/status/1198702136231526401) And in 2026 the make-it-yourself
step had gone down to the alloy: "We have since created our own new alloys and no longer use 301."
[X 2026-08-23](https://x.com/elonmusk/status/2091617925669245333)

The same goes for processes. In 2019 he posted "SpaceX foundry casting Raptor engine manifold
out of Inconel" [X 2019-02-16](https://x.com/elonmusk/status/1096722006450462721). **Our reading:** casting is
the step he names as the turbine bottleneck in 2026 (above); SpaceX already ran its own foundry for engine parts
years earlier.

## What it costs

Making things yourself is slower at first (the S-curve, chapter 03) and needs people who can do it. The 2014
patent post argues that the lasting advantage is a company's ability to attract and motivate the most talented
engineers [PAT14], which is what makes building in-house possible.

---

## Make or buy: a decision rule (our suggestion)

He has not published a rule. This one is ours, built from the three cases above.

Build it yourself if **any** of these is true:
1. **It doesn't exist** at the quality or scale you need.
2. **It is your limiting factor** and the suppliers are backlogged or few.
3. **Its price is several times its material floor** (chapter 04) and you'll buy enough to matter.

And **all** of these are true:
4. You can name the person who will own it.
5. You can survive a slower ramp while you learn.
6. It's on the path to your one number, not a side project.

Otherwise, buy it, and revisit when the limiting factor moves.

### Worked scenario (fictional)

A drone-delivery startup buys flight controllers at $420 each, 6,000 a year. Parts cost about $70. Lead time from
its one supplier has grown from 4 to 16 weeks, and the controllers are now the reason drones sit unfinished.

| Test | Answer |
|---|---|
| Exists? | Yes |
| Limiting factor? | Yes: 16-week lead time, single supplier |
| Price vs floor | $420 vs about $70: 6x |
| Owner | The firmware lead, by name |
| Survive a slow ramp? | Yes, if they keep buying from the supplier during the first 6 months |
| On the path to the one number? | Yes: cost per delivery |

Decision: build, with the supplier kept as a bridge. Year-one plan: 500 in-house units, then 3,000, then all
6,000. At an in-house cost of about $140 including labour, the saving at full volume is about $1.7m a year, and
the lead time is under their control.

### Failure modes

- **Building because it's interesting.** If it's not the limiting factor or a big cost gap, it's a distraction.
- **Cutting off the supplier on day one.** In-house ramps start slow.
- **Ignoring the people cost.** His case rests on engineers who can design from first principles.
- **Integration as identity.** He also buys what works: in the same interview he lists the parts of a gas
  turbine that can be bought, and singles out only the blades [DW 00:00:00].

### Limits

His vertical integration happens at the scale of companies with tens of thousands of staff. For a small team,
building one critical part may be the whole company's effort for a year. The decision rule above is our
reading, not his policy.

**Checks to run:**
1. Which part you buy is your limiting factor, and how many suppliers make it?
2. What is the price of your most expensive bought part, against its material floor?
3. If you built it, who by name would own it, and how would you survive the first six months?
