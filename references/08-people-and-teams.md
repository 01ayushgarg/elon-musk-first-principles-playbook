# 08 · People, hiring and reviews

## Hire for evidence of exceptional ability

> "Generally, the things I ask for are bullet points for evidence of exceptional ability. These things can be
> pretty off the wall. It doesn't need to be in the specific domain, but evidence of exceptional ability."
> [DW 01:44:16]

His bar is a few concrete things that make you say wow three times over [DW 01:44:16]. And he tells people (and
himself, as an aspiration) to trust the conversation over the CV. If a strong resume is followed by a
conversation that isn't impressive after 20 minutes, "you should believe the conversation, not the paper."
[DW 01:44:16]

## Traits you can't train, knowledge you can

> "Generally, I think it's a good idea to hire for talent and drive and trustworthiness. And I think goodness of
> heart is important. I underweighted that at one point." [DW 01:44:16]

If those are present, he says, "you can add domain knowledge", which is why most people at Tesla and SpaceX
didn't come from aerospace or cars [DW 01:44:16]. He admits his own record isn't perfect, and says he
learned by checking which hires worked out [DW 01:44:16].

**What the problem needs.** Asked about Neuralink's engineering, he listed the problems it faces: "material
science, electrical engineering, software, mechanical engineering, microfabrication, it's a bunch of engineering
disciplines, essentially." [LEX49 22:14] **Our reading:** list the problems first, and the disciplines you hire
for follow from them.

## Everyone is chief engineer

> "You really want everyone to be chief engineer. So if everyone is chief engineer means that people need to
> understand the system at a high level to know when they are making a bad optimization." [SB1 38:26 to 38:35]

His example: big effort to cut engine mass, hardly any on "proponent [sic: propellant] residuals"
[SB1 38:47 to 38:54]. Every requirement also needs a person's name, "not a department" [SB1 16:00] (chapter 02).

## Weekly reviews, skip-level, no rehearsal

> "I'm a big believer in skip-level meetings where instead of having the person that reports to me say things,
> it's everyone that reports to them saying something in the technical review. And there can't be advanced
> preparation." [DW 01:44:16]

How he runs them, by his account [DW 01:44:16]:
- **Weekly, detailed engineering reviews**, far more granular than he thinks is normal.
- **Go around the room.** Everyone gives an update; nobody is picked at random.
- **Plot the trend.** Weekly snapshots let you "mentally plot the points on a curve" and ask whether the work is
  converging.
- **Time follows the limiting factor.** Things that are going well "don't see much of me". A chip review on the
  critical path runs twice a week, usually two or three hours.

## Communicate in compressed form

> "As you try to compress complex concepts, you're perhaps forced to distill what is most essential in those
> concepts, as opposed to just all the fluff." [LEX438 00:08:37]

To communicate at all, he says, you have to model the mind of the person you're speaking to [LEX438 00:08:04].

## Judging people over time

He judges people by track record over time [LEX400 01:59:20], and warns: "Never trust a cynic." His reason:
cynics excuse their own bad behaviour by saying everyone does it [LEX400 02:00:19].

---

## How to apply it (our suggestion)

**Hiring**
1. Ask every candidate for three bullet points of evidence of exceptional ability, in any field.
2. In the interview, test one bullet in depth for 20 minutes. Write "wow" or "not wow" before reading the CV
   again.
3. Score talent, drive, trustworthiness and goodness of heart separately. Domain knowledge is a tiebreaker.
4. Six months later, compare your scores with how the hire actually did. That's your training set.

**Reviews**
1. One weekly review per limiting factor, not per team.
2. Skip-level: the people doing the work speak; their manager listens.
3. No slides prepared for the meeting. Bring the work.
4. Write each update's one number in a log. Look at the last four weeks before deciding anything.

### Worked scenario (fictional)

A 30-person robotics startup has two candidates for a controls role. A: ten years at a large automaker, strong
CV, bullet points all about job titles. B: two years of experience, bullet points include a self-built drone
autopilot and a published fix to an open-source motor driver. Twenty minutes on B's autopilot: "wow". Twenty
minutes on A's last project: A can't explain the trade-offs. They hire B, and pair B with a senior engineer for
the domain knowledge.

Their weekly actuator review was a status meeting with slides from the team lead. Switched to skip-level: four
engineers each give one update and one number (failure rate per 1,000 cycles). After four weeks the plot reads
12, 11, 11, 10: barely converging. That trend, not any one week, is what moves the founder to drop the review of
a feature that is going well and spend two hours a week on the actuator.

### Failure modes

- **Hiring the CV.** He admits to it himself: believing a hire from a famous company will succeed at once,
  which he calls the pixie dust effect [DW 01:44:16].
- **Skip-level as an ambush.** The point is information, not catching people out.
- **Reviews for everything.** His time follows the limiting factor; reviews of healthy work waste it.
- **Interviews that don't scale.** He says interviewing everyone himself "obviously doesn't scale"
  [DW 01:44:16]. Write your bar down so others can apply it.

### Limits

His hiring and review habits come from his own account; we have no data on how well they work beyond his word
and his companies' results. Skip-level reviews with no preparation suit engineering work with measurable
progress; they may not suit every function.

**Use it now:** `templates/07-hiring-scorecard.md` and `templates/06-engineering-review.md`.

**Checks to run:**
1. Could each engineer explain how their part affects the whole system's key number?
2. Which requirement has no owner's name on it?
3. For your last three hires, what was the evidence of exceptional ability?
4. Does your main review hear from the people doing the work, without rehearsal?
