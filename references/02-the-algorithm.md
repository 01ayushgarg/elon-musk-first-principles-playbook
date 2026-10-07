# 02 · The algorithm: five steps, in order

> "I have this very basic first principles algorithm that I run kind of as a mantra." [LEX438 00:44:08]

He has explained it at least twice on record: on the 2021 Starbase tour [SB1 13:29 to 26:26] and to Lex
Fridman in 2024 [LEX438 00:44:08 to 00:48:09]. The order matters.

## Step 1 · Make the requirements less dumb

> "First question the requirements, make the requirements less dumb. The requirements are always dumb to some
> degree." [LEX438 00:44:08]

> "It does not matter who gave them to you. It's particularly dangerous, if a smart person gave you the
> requirements, because you might not question them enough." [SB1 13:40]

> "Otherwise, you could get the perfect answer to the wrong question. So, try to make the question the least
> wrong possible." [LEX438 00:44:08]

**Every requirement needs a name:** "Whatever requirement or constraint you have, it must come with a name,
not a department. 'Cause you can't ask the departments, you have to ask a person." [SB1 16:00] Otherwise "you
could have a requirement that basically an intern two years ago randomly came up with." [SB1 16:16]

## Step 2 · Delete the part or process step

> "The second thing is try to delete whatever the step is, the part or the process step. It sounds very
> obvious, but people often forget to try deleting it entirely." [LEX438 00:44:53]

> "If you're not forced to put back at least 10% of what you delete, you're not deleting enough."
> [LEX438 00:44:53]

> "The bias tends to be very strongly towards, let's add this part of the process step in case we need it."
> [SB1 14:07]

> "So, you got to overcorrect. This is, I would say, like a cortical override to a limbic instinct."
> [LEX438 00:47:21]

> "Best part is no part" [X 2025-08-13](https://x.com/elonmusk/status/1955735069659947392)

## Step 3 · Simplify or optimize

> "And only the third thing is try to optimize it or simplify it." [LEX438 00:44:53]

> "I'd say the most common mistake of smart engineers is to optimize a thing that should not exist."
> [LEX438 00:44:53]

Why smart people do it: "everyone has been trained in high school and college that you gotta answer the
question, convergent logic. So you can't tell a professor, your question is dumb." [SB1 17:40 to 17:50]

## Step 4 · Accelerate cycle time

> "Any given thing can be sped up. However fast you think it can be done, whatever the speed it's being done,
> it can be done faster. But you shouldn't speed things up until you've tried to delete it and optimize."
> [LEX438 00:47:50]

> "Speeding up something that shouldn't exist is absurd." [LEX438 00:47:50]

## Step 5 · Automate

> "And then, the fifth thing is to automate it. I've gone backwards so many times where I've automated
> something, sped it up, simplified it, and then deleted it. And I got tired of doing that." [LEX438 00:48:09]

## The story: Model 3 fiberglass mats [SB1 22:21 to 24:42]

The Model 3 battery pack had fiberglass mats placed by a robot cell. He went through the steps backwards:
"So automating was a mistake. Then accelerating was mistake. Then optimizing was a mistake. And finally I said,
what the hell are these mats for?" The battery team said the mats were for noise and vibration; the noise
team said fire safety. They tested cars with and without mats and nobody could tell the difference. "So we
just deleted them and just bypass this $2 million robot cell." (Caption text; minor caption errors not shown.)

## Related production rule

> "So a very common issue with production lines is to not remove the end process testing after you diagnose
> where the problems are." [SB1 25:13]

**Use it now:** `templates/01-the-algorithm.md`.

**Checks to run:**
1. List every requirement on the thing you're building. Does each have a person's name on it?
2. What would you delete if you had to put back only one in ten?
3. Is anyone currently automating or speeding up a step nobody has tried to delete?
