---
title: "Designing for Tired, Distracted Humans"
slug: designing-for-tired-distracted-humans
book: of-course-it-went-right
category: "Systems That Assume Reality"
order: 110
summary: "Systems should assume fatigue, interruption, and partial attention."
published: true
---

# Designing for Tired, Distracted Humans

**Category:** Systems That Assume Reality
*Systems should assume fatigue, interruption, and partial attention.*

---

It is half past four in the morning on a ward, and a nurse is preparing an injection she has prepared a thousand times before. She is eleven hours into a twelve-hour shift. A patient two beds down has just buzzed, the phone at the desk is ringing, and somewhere a monitor is chirping the particular alarm that means nothing and cannot be ignored. She is competent, conscientious, and very, very tired. This is precisely the moment, every study of error will tell you, at which a good person does a careless thing.

Picture two versions of the syringe in her hand. In the first, the drug comes in a clear vial with small print, and a second drug — a different dose, a different purpose, dangerous if confused — comes in a clear vial with small print that looks almost identical. Nothing about the objects themselves resists a mistake. The only thing standing between the right injection and the wrong one is her attention, and her attention, at half past four with the phone ringing, is the one resource she does not have to spare. The system has quietly delegated its safety to the alertness of an exhausted human, which is to say it has no safety at all.

In the second version, the two drugs do not look alike. The dangerous one comes in a vial of a different shape and a jarring colour, with a connector that physically will not fit the line it must never go into. The label states the dose in large type, and the syringe will not draw past the safe volume without deliberate force. She can be tired. She can be interrupted mid-task and come back to it three minutes later. She can be running on the kind of autopilot that eleven hours builds — and the system still catches the error, because it was never relying on her not to make one. The difference between the two wards is not the quality of the nurses. It is whether someone, at the design stage, pictured her at half past four and built for *that* nurse, rather than for an alert ideal who clocks on fresh and never gets interrupted.

That second design is not luck, and it is not a triumph of individual heroism. It is the quiet, deliberate craft of building for the human who will actually show up — and it is one of the most reliable engines of safety we know how to construct.

---

## The Principle
**The strongest systems are designed for a human who is tired, interrupted, and only half paying attention — because that is the human who will actually use them. Robustness comes from making the safe action the easy action and the dangerous action the hard one, so that the right outcome survives even when attention does not.**

There is a flattering picture of the person who uses our systems: rested, focused, undivided, doing the task once and doing it deliberately. We design for that person without quite noticing we are doing it, because designing for them is easier — it lets us assume that attention will be present to fill any gap we leave. But attention is the single least reliable resource a human brings to a task, and it is least available exactly when the task matters most: late, busy, frightened, mid-interruption, on the tenth repetition of something that has become routine. A system that depends on attention to be safe has located its safety in the one place it cannot count on. The design-led alternative is to assume the attention will not be there, and to do the work of safety in the *objects and the flow* instead — in shapes that resist the wrong move, defaults that land on the right one, confirmations that wake you only at the dangerous step. The human can then be as human as they are going to be, and the outcome still holds, because nothing important was ever resting on them being more than that.

## Why It Is Inevitable
This is not a sophistication that only the most careful designers reach. Any system that runs in the real world for long enough is forced toward it, because the alternative fails in a way that is constant rather than rare.

The first reason is that fatigue and interruption are not edge cases — they are the baseline. There is no population of users who arrive rested, work without interruption, and give a single task their undivided attention from start to finish. The focused user is not uncommon; they are imaginary. Every real person is, at the moment they touch your system, somewhere on a spectrum from mildly distracted to badly depleted, and the depleted end is not the exception you can design around later. It is half the operating life of the system. A design that only works for the focused human is a design that only works in the demo.

The second reason is that the cost of a fatigue-induced error is paid where it hurts most. When a tired person makes the predictable slip — picks the wrong vial, skips the field they always skip, clicks the confirm they have clicked a hundred times — the error does not announce itself politely. It lands downstream, often invisibly, sometimes catastrophically, and always at a moment when the person who made it had the least capacity to catch it. A system that leaves these slips to be prevented by vigilance is a system that has chosen to pay for them later, at the worst possible exchange rate. The sheer expense of that, over time, pushes any serious system toward absorbing the slip in its design rather than waiting for it to surface.

The third reason is that attention degrades silently and gives no warning before it fails. A tired human does not feel themselves about to make a mistake; the whole nature of an attention lapse is that you do not notice the lapse. So you cannot solve the problem by asking people to "be more careful," because the failure mode is precisely the one that care cannot see coming. The only place a defence can live is *outside* the unreliable attention — in the shape of the thing, the structure of the step, the default the system holds. Systems that endure are the ones that put their defences there, because that is the only place defences actually survive contact with a tired human.

## How It Shows Up
- The dangerous action and the safe action are made to *look and feel different* — different shape, colour, position, weight of effort — so the hand can tell them apart even when the mind is elsewhere.
- The right choice is the default. Doing nothing, or doing the obvious thing, lands you in the safe place; you have to work to reach the dangerous one, not the other way round.
- A confirmation appears only at the genuinely irreversible step, and nowhere else — so it still means something when it arrives, rather than being one more reflexive click in a sea of them.
- The task survives interruption: you can be pulled away in the middle, come back, and the system shows you exactly where you were and what is left, instead of assuming you held it all in your head.
- There is a checklist for the steps that matter, so memory and mood are not the things keeping the sequence intact.
- The flow asks for low cognitive load at the moments of highest fatigue — fewer decisions, larger targets, plainer language — because that is when the human has the least to give.

## Why It Causes Benefit
When a system is built for the tired, interrupted human, it gains a robustness that no amount of training or exhortation can supply, because it has stopped depending on the one resource that is guaranteed to run out.

The most immediate benefit is that the predictable slips simply stop converting into harm. The mix-up that used to depend on a tired person noticing two near-identical objects no longer can happen, because the objects no longer look alike, or no longer connect, or no longer permit the wrong dose. The skipped field is now a default the person has to actively override. The class of error that fatigue reliably produces is designed out of existence, not because people became more alert, but because the system stopped requiring them to be. The work of being safe has been moved off the exhausted human and into the design, where it was done once, deliberately, by someone who was rested when they did it.

There is a deeper benefit in how such a system behaves under exactly the conditions that break ordinary ones. A system that relies on attention is most fragile when people are most depleted — which is to say it fails hardest at three in the morning, at the end of the shift, in the crisis, at precisely the moments it most needs to hold. A system built for the tired human is the reverse: the half-past-four nurse *was* the design brief, so the half-past-four case is the one it handles best. Its safety does not degrade as the humans degrade. And there is a quieter gift on top of the safety: it gives people back their attention for the things that genuinely need it. When the routine and the dangerous are both made safe by design, the human is freed to spend their scarce focus on the judgement only they can bring — the patient who looks wrong, the number that does not sit right — instead of burning it on not-mixing-up-two-vials. A system that assumes fatigue does not just prevent the tired mistake. It hands the tired person their best self back, by refusing to spend it on things a good design should have handled.

## How To Cultivate It
- Design for the worst realistic state, not the best imaginable one. Picture the specific person on their hardest day — depleted, interrupted, on autopilot, three minutes from the end of a long stretch — and build for *that* person. A system that holds for them holds for everyone; the reverse is never true.
- Make the safe action the path of least resistance and the dangerous action take deliberate effort. If the easy, automatic, low-attention move is also the safe one, fatigue stops being a threat — a tired person falls onto the safe path precisely *because* they are not trying hard. Engineer that on purpose.
- Use the physical and visual world to carry the safety, not just the words. Shape, colour, position, the connector that will not fit — these work even when nobody is reading, and at three in the morning nobody is reading. A difference you can feel beats a warning you must notice.
- Spend confirmations and alarms carefully, only at the truly irreversible step. Every needless "are you sure?" trains the human to click through it, and a confirmation everyone reflexively dismisses is worse than none. Guard the one step that matters so the guard still wakes them.
- Build for interruption as a certainty, not a possibility. Assume every task will be broken off partway through, and make the system able to show, on return, exactly where things stood and what remains — so resuming does not depend on what the person managed to keep in their head.
- Write down the steps that matter as a checklist, and put it where the work happens. A checklist is not an insult to expertise; it is the recognition that even an expert, when tired, will skip the step they have done a thousand times. Memory is the wrong place to keep anything that must not be forgotten.
- When something does go wrong, refuse "they should have been paying attention" as a conclusion. It is almost always true and almost never useful, because attention was never going to be there. The useful question is what shape, default, or step would have caught the slip without requiring the attention that was always going to be missing.

## What Good Looks Like
A system you can hand to the most depleted version of its user, at the worst hour, mid-interruption, and trust to produce a good outcome anyway. The safe action is the easy, automatic, low-effort one, so a tired person falls onto it without trying; the dangerous action is made deliberately awkward, so it cannot be reached by accident; and the difference between them is carried in things you can see and feel rather than small print you must read. Confirmations are rare and therefore still mean something. The task survives being broken off and resumed, because it never assumed the human was holding it all in mind. Nothing important rests on anyone being alert, rested, or undistracted — because all of that was assumed absent at the design stage, and the work of being safe was done there, once, by a rested designer, rather than demanded fresh from every exhausted user forever. The result is a system that is at its best exactly when conditions are at their worst, and that, as a side effect, gives people their scarce attention back to spend on the judgement only they can supply. It was built, from the first sketch, for a tired and distracted human — and that is exactly why it keeps the tired and distracted human safe.

## A Reflective Question
Think of a task in your environment where the cost of a slip is high. Now picture the person doing it at the end of a long day, interrupted halfway through, running on autopilot — and ask honestly whether the system is built to catch their mistake without their attention, or whether its safety is quietly resting on a level of alertness that the person, on their hardest day, was never going to have.
