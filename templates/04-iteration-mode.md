# Template 04 · Pick the iteration mode

Match how fast you change things to what a failure costs. Source: `references/05-iteration-risk-and-speed.md`
[SB2 05:35 to 08:33].

| Mode | When a failure costs... | How to work |
|---|---|---|
| **Dragon** | People's safety, money they trust you with, legal exposure, data loss | "There can be no failures ever." Reviews, staged rollout, rollback plan, tests first |
| **Falcon** | Real customers who rely on it, but recoverable | "a little less conservative" Feature flags, canaries, ship weekly |
| **Starship** | Nobody's on board: internal, prototype, test users who opted in | "iterating rapidly" Ship daily, expect to blow things up, learn fast |

## Your work

| Thing you're building | Mode it should be | Mode you're running it in | Fix |
|---|---|---|---|
| | | | |
| | | | |
| | | | |

## Two checks

1. **Are you treating a Starship like a Dragon?** Signs: weeks of review for something no customer sees,
   "it worked before" as the reason not to change it. [SB2 08:07]
2. **Are you treating a Dragon like a Starship?** Signs: shipping payments or data changes without a rollback.

**Where can the risky learning happen off the main product?** (His example: a separate test program,
Grasshopper, because Falcon 9 carried customers [SB3 17:32 to 17:49].) ______________

**Incentives:** what happens to someone here when a change goes wrong, and when it goes right? If the
punishment is big and the reward is small, people stop changing things. [SB2 07:34] ______________
