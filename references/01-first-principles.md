# 01 · First-principles thinking

Citation IDs are in `SOURCES.md`: `[TED13 mm:ss]` TED talks · `[LEX49 mm:ss]` `[LEX400 hh:mm:ss]`
`[LEX438 hh:mm:ss]` Lex Fridman · `[DW hh:mm:ss]` Dwarkesh Podcast · `[SB1 mm:ss]` / `[SB2]` / `[SB3]` Starbase
tours · `[MP1]` `[MP2]` master plans · `[IAC17]` `[NS17]` `[HYP13]` `[MIS13]` `[PAT14]` papers and posts ·
`[X date]` posts.

## What he means

> "Generally I think there are -- what I mean by that is, boil things down to their fundamental truths and
> reason up from there, as opposed to reasoning by analogy. Through most of our life, we get through life by
> reasoning by analogy, which essentially means copying what other people do with slight variations."
> [TED13 19:19]

He has posted that "Reasoning from first principles is a superpower" [X 2025-02-17](https://x.com/elonmusk/status/1891351204862783701), and
says the tools of physics are "really just critical thinking" that apply to "really any arena in life"
[LEX400 01:10:59]. In a 2024 post he named two of those tools: "first principles analysis and thinking in the
limit" [X 2024-03-05](https://x.com/elonmusk/status/1764976308977594418). A month later he repeated the claim
that these tools travel: "The mental tools of physics are a superpower that applies to anything, not just
physics" [X 2024-04-30](https://x.com/elonmusk/status/1785134934660616695).

## Think in the limit

> "For something important you need to reason with from first principles and think about things in the limit
> one direction or the other." [LEX400 01:10:59]

Two of his examples:
- **Compute.** Even with the whole power of the sun, he says, you would still care about useful compute per
  watt [LEX400 01:10:59]. In 2026 he ran the same move on power: once you ask what share of the sun's output you
  are harnessing, he argues, you end up needing to go to space [DW 00:00:00].
- **Hyperloop.** He framed the design by its two extremes: one tube full of air pushed by fans, which friction
  makes "impossible for all practical purposes", and one held at near vacuum, where "All it takes is one leaky
  seal" to stop the system. He picked the point between them, low pressure that standard pumps can hold
  [HYP13].

**The move:** push one variable to its extreme in each direction and see what still matters, then choose the
point between the extremes that survives the real world.

A small dated example of sizing an idea at its limit before chasing it: when someone suggested in 2021 that
Starship drop its landing propellant and fall into a giant net, he said SpaceX had discussed it and "Could just have it land on a big net or bouncy
castle. Lacks dignity, but would work." Then the number: "optimized landing propellant is only ~5% of dry mass,
so it's not a gamechanger" [X 2021-03-10](https://x.com/elonmusk/status/1369489056350883840). **Our reading:**
take the saving to its limit (all of it gone) and ask what that is worth. If the best case is 5%, spend the
effort elsewhere.

## Reality is the judge

> "You have to test any conclusions against the ground truth of reality. Reality is the ultimate judge. Like
> physics is the law, everything else is a recommendation." [LEX400 00:40:01]

He holds the scientific method in the same terms: something is true "to the degree that it is testably so"
[LEX49 03:16]. And he aims to "minimize how often you're confidently wrong", not to be right every time
[LEX400 00:37:02].

On how an AI system should handle truth, he made the same point about physics: you don't claim certainty, "but a
lot of things are extremely likely, 99.99999% likely to be true." [LEX438 00:57:57]

## Frame the question first

> "Sometimes the answer is arguably the easy part, trying to frame the question correctly is the hard part.
> Once you frame the question correctly, the answer is often easy." [LEX438 01:21:02]

He credits the idea that the question is harder than the answer to Douglas Adams [TED22 47:50].

---

## How to apply it (our reading)

These steps are our summary of the quotes above, not a procedure he has published.

1. **Write the goal in one line,** in a unit you can measure (*cost per customer served*, *minutes to first
   value*).
2. **Write the conventional answer** and the reason given for it. Mark each reason as either a law (physics,
   maths, law of the land, what the customer actually needs) or a habit (*everyone does it*, *the last team
   did it*).
3. **List only the laws.** Rebuild the answer from those.
4. **Push one variable to each limit** (zero, infinite, the whole market). Note what still matters.
5. **Test the rebuilt answer against reality** with the cheapest experiment you can run this week.
6. **Ask a friend to find the flaw.** He tells people to "really pay attention to negative feedback, and solicit
   it, particularly from friends" [TED13 19:19].

### Worked scenario (fictional)

A five-person B2B startup plans a 12-week sales cycle *because enterprise deals take a quarter*.

| Part of the cycle | Weeks | Law or habit? |
|---|---|---|
| Buyer's security review | 3 | Law: the buyer can't sign without it |
| Legal review of the contract | 2 | Law, but a standard contract can cut it |
| Three demos to three committees | 4 | Habit: copied from a competitor's playbook |
| Pilot "to build trust" | 3 | Habit: no buyer asked for it |

Rebuilt from the laws only: security review started on day one, in parallel with a standard contract. Six
weeks, not twelve. In the limit (a buyer who already trusts you completely), the floor is the security review,
so that is where to spend effort: a ready-made security pack. The cheapest test: offer the pack to the next
three prospects and time it.

### Failure modes

- **Calling a habit a law.** *Our customers expect it* is a habit until a customer has said it.
- **Stopping at the analogy you like.** Copying a better company is still reasoning by analogy.
- **Rebuilding everything.** First principles is for "something important" [LEX400 01:10:59], not for every
  choice. Use it on the one number that decides whether you win (chapter 04).
- **Skipping the test.** A first-principles answer that hasn't met reality is a hypothesis.

### Limits

His examples are physics-bound: propellant, steel, watts. In software and services the "laws" are softer
(customer behaviour, regulation, team skill). Treat them as measurements to take, not constants to assume.

**Checks to run:**
1. What's the conventional answer to your problem? Which parts are law, and which are habit?
2. Push one variable to its limit. What still matters?
3. What would you need to see to be proven wrong? Have you asked a friend to look for it?
