---
title: "Optimisation Breaks What It Doesn't Understand"
slug: optimisation-breaks-what-it-doesnt-understand
book: of-course-it-went-right
category: "Why This Was Never an Accident"
order: 124
summary: "Removing \"inefficiencies\" without understanding their purpose dismantles robustness."
published: true
---

# Optimisation Breaks What It Doesn't Understand

**Category:** Why This Was Never an Accident
*Removing "inefficiencies" without understanding their purpose dismantles robustness.*

---

A new operations lead inherits a small regional water utility and, within a fortnight, finds three things that offend him.

The first is a reservoir kept deliberately below its maximum level — a third of its capacity held empty, year-round, doing nothing. The second is a pump house with two pumps where one would plainly suffice; the second pump runs perhaps a dozen days a year. The third is a standing instruction that the night crew physically walk the main line once a week and log pressures by hand, even though there are sensors that report the same numbers automatically to a screen in the control room. To a man who has been brought in to find savings, these are not subtle. They are money sitting in plain view: storage paid for and unused, a redundant pump bought and maintained, a labour cost for a task a machine already does.

So he reads it as waste, because from where he stands it looks exactly like waste, and he is not wrong about the arithmetic. The empty third of the reservoir really is capacity nobody is using. The second pump really does sit idle most of the year. The night walk really does duplicate the sensors most weeks. He proposes filling the reservoir to capacity to defer a future build, decommissioning the spare pump, and dropping the manual round. The numbers are clean. The case is strong. Everyone agrees it is a sensible tightening of a slack operation.

What he has not yet learned — because nobody wrote it down and the people who knew it have retired — is that the reservoir is held low so it can *absorb* a storm surge without overtopping; that the spare pump is what keeps the town in water on the day the main pump fails, which it will; and that the night walk catches the slow pressure drift that the sensors, calibrated to flag only sudden faults, are blind to. Every one of the "inefficiencies" is doing a job. The job is simply invisible on a normal day, which is most days, which is exactly why it looks like nothing.

The slack was not an oversight that survived because no one had got round to cutting it. It was put there, on purpose, by people who had watched the system fail. That it looks like waste to a fresh eye is not evidence that it is waste. It is evidence that robustness, when it is working, looks like spare capacity doing nothing — right up until the day it is the only thing standing between you and the flood.

---

## The Principle
**The inefficiencies an optimiser is itching to cut — the slack, the redundancy, the slow step, the spare capacity, the apparently pointless ritual — are frequently load-bearing. They are what makes the system robust to shocks, and they look like waste precisely because, on an ordinary day, robustness has nothing to do. Cut what you do not understand and the system runs leaner right up until it shatters.**

The reasoning runs the wrong way round in most optimisation. The optimiser sees a part of the system that is not earning its keep on a normal day and concludes it is not earning its keep at all. But many of the most important parts of a robust system are not there for the normal day. They are there for the bad day — the surge, the failure, the slow drift — and on every other day they will, by design, appear to be doing nothing. Their idleness is not a sign that they are unnecessary. It is the *cost of insurance*, paid quietly across all the good days so the system survives the rare bad one. To read that idleness as waste is to mistake the premium for the claim, and to cancel the policy because you have not yet had the fire.

## Why It Is Inevitable
This mistake is not a sign of a careless optimiser. It is the default outcome of competent people doing exactly what they are asked to do, and it recurs because three things are almost always true at once.

The first is that **robustness is invisible when it is working.** A safeguard that is doing its job produces no events — no flood, no outage, no drift — and absence of events reads, to anyone measuring activity, as absence of value. The spare pump that never runs and the spare pump that is genuinely useless look identical from the dashboard. The only way to tell them apart is to understand *why* the spare exists, and that understanding lives outside the numbers.

The second is that **the reason is rarely written down.** Slack and redundancy tend to be added in the aftermath of a failure, by people who lived through it, as a "never again." Then those people leave, the failure recedes from memory, and what remains is the safeguard without its rationale — a stripped fuse, a standing instruction, a held-back capacity that now looks arbitrary. The justification decayed faster than the structure it justified, so the structure is left looking like an accident.

The third is that **optimisation is rewarded for cutting, not for understanding.** The person who removes a cost gets a visible, immediate, measurable win. The person who pauses to ask *why is this here before I remove it* gets nothing measurable for the asking, and looks slower for it. The incentives push hard toward action and away from the patient inquiry that would distinguish dead weight from a load-bearing wall. So competent optimisers, doing precisely the job they were given, cut the fence they do not understand — because the system that would have rewarded them for understanding it first does not exist.

Put those three together and the result is not bad luck. It is the predictable behaviour of a smart person, well incentivised, operating on a system whose robustness is invisible and whose reasons are lost. Which is exactly why the systems that *survive* optimisation did something deliberate to prevent it.

## How It Shows Up
- A part of the system sits idle most of the time, and someone competent and well-meaning points at it as obvious waste — the spare, the buffer, the slack, the step that "we never actually need."
- A long-standing rule or ritual has no living owner who can say why it exists, only people who follow it out of habit — which reads as the perfect candidate for cutting.
- An efficiency drive removes a redundancy and the system runs visibly *better* afterwards — faster, cheaper, cleaner — for weeks or months, because the shock the redundancy guarded against simply has not arrived yet.
- The justification for a safeguard has decayed faster than the safeguard: the structure remains, the reason is gone, and the gap is read as evidence the structure is pointless.
- The case for cutting is made entirely from normal-day data, because that is the only data there is — the bad-day data, by definition, is rare and absent from the spreadsheet.

## Why It Causes Benefit
When a system is built — or governed — so that nobody removes a thing before understanding why it is there, it gains a kind of resilience that pure efficiency can never buy: it keeps the safeguards it cannot currently justify, *because* it cannot currently justify them, until someone has done the work to be sure.

The benefit is that the system survives its bad days. The held-back reservoir absorbs the surge that would otherwise have flooded the town. The idle pump carries the load the day the main one fails. The pointless night walk catches the drift before it becomes a burst main. None of these pay off on a normal day — but normal days were never the threat. The threat was the rare shock, and the slack that looked like waste is precisely the thing that turns a rare shock from a catastrophe into a non-event. A robust system spends its good days looking slightly over-provisioned and its bad days looking like genius, and the two are the same decision seen under different weather.

There is a compounding benefit, too, in the *posture* itself. An organisation that treats unexplained structure with curiosity rather than contempt — that asks "why is this here" before "can we cut this" — accumulates understanding instead of shedding it. Each time it investigates a safeguard before touching it, it either learns the safeguard is load-bearing and keeps it knowingly, or learns it is genuinely dead and removes it *with confidence rather than luck*. Both outcomes leave the organisation smarter than it was. The efficiency drive that cuts blind gets lucky or it does not; the one that understands first is never gambling. Over time, the careful organisation ends up both leaner *and* more robust than the reckless one, because it only ever cut the things that were actually safe to cut — and that is not an accident of temperament. It is what happens when "understand before you remove" is built into how the place works.

## How To Cultivate It
- Adopt the fence rule explicitly: do not remove a thing until you can say why it is there. If nobody can explain the reason, that is a signal to *investigate*, not a licence to cut — the absence of a known reason is the most dangerous case, not the safest.
- Treat slack, redundancy and spare capacity as deliberate robustness until proven otherwise. Make the burden of proof fall on the person removing the safeguard, not on the safeguard to justify its continued existence on a normal day.
- Hunt for the bad-day case before deciding. Ask, of any "inefficiency": what shock might this be guarding against, and have we actually had that shock recently enough to remember it? The thing that has not failed lately is not the thing that cannot fail.
- Write the reason down at the moment a safeguard is created — the "never again" that prompted it, in plain words, attached to the structure — so the justification does not decay faster than the thing it justifies and leave a future optimiser staring at an unexplained rule.
- When you do remove a redundancy, remove it as a reversible experiment where you can, and watch for the bad day, rather than declaring victory from the calm weeks immediately after. The leaner system that "runs fine" has not yet been tested by the only thing the redundancy was for.
- Reward the person who pauses to understand, not only the person who cuts. An organisation that gives a visible win for removing cost and nothing for understanding it will keep cutting fences, because that is what it pays for.

## What Good Looks Like
A system whose spare capacity, redundancy and slow steps are kept *knowingly* — where someone can tell you, for each apparent inefficiency, which shock it absorbs and why it earns its keep across the bad days even though it idles through the good ones. Where an optimiser arriving with a sharp eye and a strong cost case is welcomed, and then asked, gently and as a matter of routine, to find out *why* each thing exists before removing it — and where doing so is treated as the real work, not a delay to it. Where the reasons for safeguards are written down at their creation and survive the departure of the people who lived through the failure, so robustness does not quietly decay into things that merely look arbitrary. Where the things that genuinely are dead weight do get cut — cleanly, confidently, because they were understood first — and the things that are load-bearing are kept, also because they were understood first.

The result looks, on any ordinary day, slightly less efficient than the system that cut everything it could. And then the bad day comes — the surge, the failure, the drift — and the careful system simply absorbs it and carries on, while the lean one shatters and everyone asks how nobody saw it coming. They did see it. It was written on the structure they removed, in capacity that looked like waste right up until it was the only thing holding. The robustness that saved the careful system was not luck. It was engineered, kept on purpose, and defended against the entirely reasonable instinct to tidy it away.

## A Reflective Question
Look at the thing in your system that everyone agrees is wasteful — the slack, the spare, the slow step nobody can quite justify. Before you cut it: can you actually name the shock it might be there to absorb, or are you certain it is waste only because you have not yet had the bad day it was built for?
