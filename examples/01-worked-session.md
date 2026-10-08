# Worked example: running the algorithm on "Quillbox"

> **Fictional.** Quillbox, its people and every number below are invented to show how the skill works. Nothing
> here is a claim about any real company. Quotes from Musk are real and cited.

## What the founder sent

```text
Run Elon Musk's algorithm on my startup.

What we make: Quillbox turns support tickets into help-centre articles automatically.
The goal: get a new customer from signup to first published article in under 10 minutes.
The process or product to attack: our onboarding. Today it takes 6 days on average.
Unit economics: $49/month plan. Cost to serve ~$31/customer/month.
Team: 5 people. 2 engineers, 1 designer, 1 support, me.
What's slow or expensive right now: onboarding, and our AI bill.
```

## What the skill asked back

The skill doesn't guess numbers. Before naming the limiting factor, it asked:

```text
1. What share of trials never publish an article?
2. How do trials that publish in week one convert, compared with the rest?
3. What makes up the $31 cost to serve?
4. When a published article is wrong, who sees it?
```

The founder replied:

```text
1. About 40% never publish (last 90 days, 212 trials).
2. Week-one publishers convert at roughly 3x the others.
3. Model calls ~$9, hosting ~$2, support time on the onboarding call ~$14, the rest tooling.
4. The customer's own users. It goes straight to their public help centre.
```

## What the skill returned

### The limiting factor

**Onboarding time (6 days).** By the founder's numbers, 40% of trials never publish an article, and the ones
that publish in week one convert at about 3x the rate. Nothing else on the list matters until this moves. → `references/06-the-limiting-factor.md`

### Step 1 · Requirements, each with a name

| Requirement | Name on it | Verdict |
|---|---|---|
| Connect the helpdesk before anything else | Nobody remembers. Designer thinks it was the first investor demo | **Change:** start from one pasted ticket |
| Customer approves the style guide | Founder, 2024 | **Drop for trial:** use a default, edit later |
| Security review call for every trial | Support lead, after one enterprise ask | **Drop for trial:** enterprise only |
| Import the full ticket history | Engineer, *to make the AI better* (fictional) | **Change:** last 200 tickets |

"It's particularly dangerous, if a smart person gave you the requirements, because you might not question
them enough." [SB1 13:40] The style-guide requirement was the founder's own.

### Step 2 · Delete

11 onboarding steps → 4. Deleted: style guide, security call, team invite, billing before value, workspace
naming, tour video, two confirmation emails. Put back one (team invite, because customers asked within a
week): 1 of 7 back, about the "10%" he expects. [LEX438 00:44:53]

### Step 3 · Simplify

Of the 4 steps left, the article editor had 14 formatting options. Cut to 3. The team had been tuning the
article-quality model for a flow most trials never reached: "the most common mistake of smart engineers is to
optimize a thing that should not exist." [LEX438 00:44:53]

### Step 4 · Accelerate

Import of 200 tickets took 40 minutes because of a sequential job. Run it in parallel: 3 minutes.

### Step 5 · Automate

Only now: auto-draft the first three articles while the import runs. Had they automated in week one, they'd
have automated the security call.

### Cost floor

| Input per customer per month | Cost |
|---|---|
| Model calls | $9 |
| Hosting and storage | $2 |
| **Floor** | **$11** |
| **Current cost to serve** | **$31** |

The $20 gap was mostly human: support time on the onboarding call ($14, the founder's figure). The onboarding cut removes most of it.
Their "cost per ton to orbit" is cost to serve per customer. [SB1 06:20] → `references/04-cost-from-first-principles.md`

### Iteration mode

| Thing | Should be | Was |
|---|---|---|
| Onboarding flow | Starship (trials only) | Dragon (two reviews per change) |
| Publishing to customer help centres | Dragon (it's their public site) | Falcon |

Swap them. → `references/05-iteration-risk-and-speed.md`

### This week

1. Ship the 4-step onboarding to new trials only. Owner: engineer A.
2. Founder sits in on 10 trial onboardings live, to go where the limit is. → `references/06-the-limiting-factor.md`
3. Add a staged rollout and undo to publishing. Owner: engineer B.

**The number:** median minutes from signup to first published article. Today: about 8,600. Target: 10.

### Where to be careful

He says he's "pathologically optimistic on schedule" [LEX400 01:54:38], and sets deadlines he thinks have
about a 50% chance [DW 01:44:16]. Ten minutes is the goal. The team's coin-flip estimate for this month is under
one day, so that's the deadline.

## The result (invented)

Median time to first article went from 6 days to 2 hours in three weeks. Trial-to-paid rose from 9% to 14%.
The next limiting factor was the price page.
