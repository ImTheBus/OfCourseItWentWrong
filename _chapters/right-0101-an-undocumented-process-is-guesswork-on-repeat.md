---
title: "An Undocumented Process Is Guesswork on Repeat"
slug: an-undocumented-process-is-guesswork-on-repeat
book: of-course-it-went-right
category: "Systems That Assume Reality"
order: 101
summary: "Documentation works as shared memory, not control."
published: true
---

# An Undocumented Process Is Guesswork on Repeat

**Category:** Systems That Assume Reality
*Documentation works as shared memory, not control.*

---

A finance team runs its month-end close the way it has always run it: through one person who knows where everything is.

Her name doesn't matter, because every team has her. She knows that the reconciliation has to wait until the warehouse figures land, but not the ones in the first export — the corrected ones that come through about an hour later, because the first export double-counts a particular kind of return. She knows which of the two spreadsheets named almost identically is the live one. She knows that the number from the payments provider always arrives a day late and that you accrue an estimate and true it up next month rather than waiting. She knows the order in which the journals have to post or the system throws an error that looks alarming and means nothing. None of this is written anywhere. It doesn't need to be, because she's always there, and she's never wrong, and the close goes out clean and on time every single month.

Then she breaks her wrist falling off a kerb, and is signed off for three weeks, and one of those weeks is month-end.

What happens next is not a disaster, exactly. It is something quieter and more instructive. A capable colleague is handed the close and does his honest best to reconstruct it from the artefacts left behind — the spreadsheets, the half-remembered remarks, the folder structure that made sense to someone else. He guesses well in most places and badly in a few. He uses the first warehouse export, the one that double-counts. He waits for the payments figure instead of accruing, so the close runs two days late. He posts the journals in an order the system doesn't like and spends an afternoon convinced something is broken. The numbers eventually come out roughly right, after a great deal of effort and one genuinely worrying evening, and the lesson everyone takes away is "thank goodness she's back next week."

The actual lesson is different. The close was never a stable process. It was a performance that one person could give flawlessly and nobody else could give at all, because the process lived entirely in her head — and a process that lives in one head isn't a process. It's a guess that happens to keep landing because the same person keeps making it. Write it down and you don't constrain her; you free everyone else from having to re-derive it badly, and you free *her* from being the single point of failure she never asked to be.

---

## The Principle
**A process that exists only in someone's head is re-derived from scratch every time it's run by anyone else — and re-derived slightly differently, slightly wrongly, every time. Writing it down turns private, repeated guesswork into shared memory that anyone can use and everyone can improve. The documentation is there to enable judgement, not to replace it.**

The common picture of documentation is bureaucratic: forms to fill, boxes to tick, a binder nobody reads, written by people who don't do the work for people who'd rather not be told how. That picture is real, and it's why so many capable people quietly resist documenting anything — they've only ever met documentation as control. But that's one species of the thing, and a degenerate one. The other species is shared memory: the record of how something is actually done, why it's done that way, and where the traps are, written by the people who hit those traps so the next person doesn't have to. The first species constrains. The second liberates. They look superficially alike on the page, which is the whole source of the confusion, but they do opposite things to the people who use them. The principle is about the second kind, and the distinction between them is not a footnote — it is the entire point.

## Why It Is Inevitable
This isn't a virtue that the best environments happen to cultivate out of tidiness. It's something they're driven to, because the alternative fails in a way that's invisible right up until it's expensive.

Undocumented process fails because **knowledge that lives only in a person leaves with that person, and degrades in the meantime.** Not through anyone's fault — simply because that's how human memory and human availability work. The expert goes on leave, or off sick, or to a better job, and the knowledge goes with them, partially or wholly, gracefully or otherwise. And even while they're present, anyone else who has to run the thing is reconstructing it from fragments and inference — guessing, in good faith, and guessing differently each time because there's no fixed reference to guess against. The process drifts, because each person's private version of it drifts, and there's nothing to anchor them to a common one. What looks like a stable, repeatable operation is actually a fresh improvisation every cycle, performed competently enough that nobody notices it was improvised until the day the improviser changes.

You can't outrun this with talent. The more capable your expert, the more invisible the problem, because a sufficiently good person papers over the absence of a process with sheer fluency — they never need the documentation, so they never write it, so the dependency on them deepens precisely *because* they're excellent. The failure is structural, not personal, which is exactly why good people and bad luck produce it together. So any environment that wants its work to survive the people who currently do it is pushed, sooner or later, toward the same answer: get the process out of the head and onto something durable and shared. The environments that do this on purpose, early, are simply the ones that didn't have to learn it from the bad month.

## How It Shows Up
- The phrase "ask her, she knows how it works" is the documentation, and the answer changes slightly depending on who you ask and when.
- A new starter is handed a task with no written steps and learns it by interruption — a dozen small questions to whoever's nearest, each answered from memory and not always the same way twice.
- A single person's leave, illness, or departure quietly turns a routine task into a minor crisis, and everyone treats this as bad luck rather than as a predictable consequence of where the knowledge lived.
- The same questions get asked and answered repeatedly, because the answer is never captured anywhere the next person can find it.
- Where documentation does exist, it's a dead artefact — written once for an audit, never opened, already wrong — which everyone has learned to ignore, deepening the belief that documentation is pointless.
- Small, hard-won lessons ("don't use the first export") are held privately and rediscovered painfully by each new person, because there's no shared place for the team's memory to accumulate.

## Why It Causes Benefit
When a process is genuinely written down — as shared memory rather than as control — an environment gets something that feels almost unfair in how much it gives back for the effort.

The first gift is continuity. The work no longer depends on a particular person being present and well. Anyone competent can pick up the documented process and run it, which means leave can be taken, illness survived, holidays enjoyed, and departures absorbed, without the operation lurching. The single point of failure dissolves — not because the expert became less valuable, but because their knowledge stopped being trapped inside them. That's a kindness to the expert as much as to the team: nobody should have to be irreplaceable, because irreplaceable means never truly off.

The second gift is that the process can finally *improve*, which an undocumented one essentially cannot. You cannot refine what you cannot see. When the steps and the reasons are written down, they become a thing the whole team can look at, question, and better — someone spots the redundant step, someone else adds the trap they just hit, the expert corrects a guess that had quietly become a habit. The documentation accumulates the team's learning instead of letting each person rediscover it alone. Private guesswork gets the same answer every time at best; shared memory gets a *better* answer over time, because every run can leave the record cleaner than it found it.

And the third gift, the one that depends entirely on it being memory and not control, is that good documentation captures the *why*, which means it enables judgement rather than replacing it. A script that says "use the second export" makes a person who hits an unexpected third export helpless. A record that says "use the second export *because* the first double-counts returns" makes that same person able to reason — to recognise that the principle is "avoid the double-count" and apply it to a situation the document never anticipated. Documentation that carries its reasons doesn't turn people into compliant machines; it turns them into capable operators who understand what they're doing and can therefore handle what the document didn't foresee. That is the difference between memory that frees and control that constrains, and it is the whole reason this works.

## How To Cultivate It
- Write the process down at the moment it's being run, by the person running it, not retrospectively for an audit. Documentation written by the doer, while doing, captures the real traps; documentation written by an observer for a binder captures only the official fiction.
- Capture the *why*, not just the *what*. "Use the second export" is control and breaks on contact with the unexpected. "Use the second export because the first double-counts returns" is memory, and lets the next person reason past situations you never imagined. The reasons are the part that enables judgement, so they're the part that matters most.
- Treat the document as living, not finished. Make updating it a normal part of running the process — every person who hits a new trap adds it, every person who finds a redundant step removes it. A document that can't be edited by its users rots into the dead-artefact kind everyone learned to ignore.
- Test it by having someone *else* run the process from the document alone, and watch where they stumble. The stumbles are the gaps the expert couldn't see, because they'd long since stopped noticing what they knew. A process is only really documented when someone unfamiliar can run it from the page.
- Resist the urge to script people into compliance. The goal is a capable operator who understands the process, not an obedient one who executes it blindly — so write for judgement, leave room for it, and explain rather than instruct wherever you can.
- Make documenting a normal, valued part of the work rather than overhead to be skipped under pressure. The cultures that manage this treat "it isn't written down" as an unfinished state, the same way they'd treat a job half-done — because that's exactly what it is.

## What Good Looks Like
An environment where the important processes live on something durable and shared, not in particular heads — where the month-end close, or its equivalent, can be run cleanly by a capable colleague from the written record, and the person who usually runs it can break her wrist in peace. Where the documentation carries its reasons, so the people using it can exercise judgement when reality departs from the script, rather than freezing. Where the record is alive: edited by the people who run the process, improved a little on every cycle, accumulating the team's hard-won lessons instead of forcing each person to rediscover them painfully and alone. Where a new starter is handed a task *and* a clear account of how it's done and why, and can therefore become useful in days rather than being trained by a hundred interruptions over months. Where documenting is treated as part of finishing the work, not as bureaucratic overhead — and where, crucially, nobody experiences the documentation as a leash, because it was built as memory to free them rather than as control to bind them. The expert is still expert; she's just no longer a single point of failure, and the thing she knew is now something the whole team knows and keeps making better.

## A Reflective Question
Which of your important processes lives only in one person's head right now — and if that person were unreachable for a month, would the rest of you be running the real process, or guessing at a reconstruction of it? And when you imagine writing it down, is your instinct that you'd be capturing memory to free people, or imposing control to constrain them — because which of those you build is entirely your choice, and it determines whether anyone will ever actually use the thing.
