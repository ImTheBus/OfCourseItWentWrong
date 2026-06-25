---
title: "The Handoff Is Where It Breaks"
slug: the-handoff-is-where-it-breaks
book: of-course-it-went-wrong
category: "Team dynamics"
order: 143
summary: "Work survives inside each team and degrades in the space between them."
published: true
---

# The Handoff Is Where It Breaks

**Category:** Team dynamics
*Work survives inside each team and degrades in the space between them.*

---

A hospital ward, late in the evening. The day nurse has cared for one particular patient for twelve hours, and she knows a hundred small things about him that never made it onto the chart. That he plays his pain down when you ask. That his daughter came in at three and pressed a question about the new medication. That the medication itself seemed to leave him drowsy in a way that was hard to name but felt worth watching. At shift change she has eight patients to hand over in fifteen minutes, so for each she gives the essentials — diagnosis, drugs, the things already flagged on the board — and moves on.

The night nurse is good at his job. He takes the handover seriously, asks sharp questions, writes things down. But the channel is fifteen minutes wide and her knowledge is twelve hours deep, and the thing about the drowsiness — a hunch, not yet a fact, awkward to phrase, easy to let go when you are on patient six of eight with four minutes left — does not make the crossing. It was real. It mattered. It simply did not fit through the door.

Overnight the patient deteriorates in more or less the way she had half-sensed and never quite said. When it is reviewed, both nurses are found to have done their jobs well. The handover happened. It was thorough by the standards of handovers. The failure was not that either nurse was careless, and not that nobody owned the patient — both owned him, in sequence, attentively. Nobody dropped the patient. The patient was handed over, carefully, by one good owner to another. The loss happened in the handing.

---

## The Principle
**A handoff is not a neutral pipe that moves work unchanged from one place to another; it is a translation through a narrower medium, and translation loses.**

The person handing the work over holds it as a rich, lived, partly tacit understanding. To pass it on, they have to compress that understanding into an artefact — a verbal summary, a ticket, a spec, a deck, an email, a meeting. The artefact is always lower-bandwidth than the understanding behind it. The receiver then decompresses the artefact back into their own rich understanding, but they are rebuilding from the compressed version, so they reconstruct something subtly different and fill the gaps with their own assumptions. Both ends are competent. The work is correct on departure and corrupted on arrival, and the corruption lives in the channel, not in either person.

This is a different failure from a seam nobody is watching. When nobody owns the whole, the work dies in a gap because no one is attending the join. Here the join is staffed on both sides — there is a real handover, a real ticket, two named owners who both turn up — and the work degrades anyway. An unattended seam loses work to neglect; a handoff loses work to bandwidth.

The part that catches people out is that the loss is invisible to both sides at the moment it happens, because each side experienced a clean exchange. The sender said what they meant to say. The receiver understood what they were told. Neither was wrong about their own half. The gap is the difference between the two halves, and a difference is exactly the thing nobody in the room can see.

## Why It Is Inevitable
This is structural, not a matter of effort. Keep the sender honest and competent throughout and the loss still happens, for three reasons.

First, most of what an expert knows is tacit and resists encoding. The day nurse's hunch, an engineer's feel for which edge case will bite, a salesperson's read on a client — this knowledge is real and load-bearing, but it lives below the level of words. You cannot hand over what you cannot fully articulate, and you rarely even notice it is there until it is missing. So the richest, most valuable content is exactly the content least likely to survive the transfer.

Second, the channel is always too narrow, and narrowing it is rational. Handoffs happen under constraint — fifteen minutes, a ticket template, a one-page brief, a meeting with an agenda. Compression is not laziness; it is necessity. Nobody has time to transfer twelve hours of context, so they transfer the essentials, and "the essentials" are chosen under pressure by someone who cannot fully see what the receiver will end up needing. The medium forces a lossy summary, and the summary looks complete from the sending side.

Third, both ends mistake a successful transmission for a successful transfer. The sender feels heard. The receiver feels informed. The ritual completed cleanly. Nobody experiences the gap, because a gap is the absence of something, and you cannot notice the absence of context you did not know was needed. So there is no signal at the moment of loss. The handoff feels most successful at precisely the moment the unspoken thing has quietly failed to cross. It is the same false green that lets a failing system report health — only here the false green is the warm feeling of a clean handover, not a number on a dashboard.

## How It Shows Up
- "But it was all in the handover" — said by a sender who is genuinely right that they passed it on, about work that arrived missing the point.
- The receiving team building something internally coherent, well-executed, and subtly not what was meant — and being praised for it right up until someone notices.
- Caveats, edge cases, and the reason we do it this way dropping out of a spec while the literal instructions survive intact.
- Work degrading a little at every hop — sales to product to engineering to support — where each crossing is individually fine and the cumulative drift is enormous.
- Receivers filling unstated gaps with their own assumptions and never knowing they did, because an unstated assumption looks identical to a shared one.
- Questions the receiver never asked, because they did not know what they did not know — the loss hides in the unknown unknowns, not the disputed knowns.
- A review that finds the handover "happened" and was "adequate," and the thing still went wrong, and everyone agrees the process was followed.
- A handoff that uses all the right shared words to feel complete while carrying none of the meaning behind them.

## Why It Causes Damage
The work that arrives is plausible, which is what makes it dangerous. A handoff that lost content does not produce obvious garbage; it produces a competent, confident, almost-right output. Almost-right passes review, ships, and is trusted, because it bears every mark of good work. The error rides downstream undetected precisely because the receiver did such a good job rebuilding from the thin version. Garbage gets caught. Plausible-but-wrong does not.

The loss also compounds across the chain, and the blame lands at the end. In a process with several hops, each transfer sheds a little, and the drift accumulates silently until the final receiver produces something visibly wrong. They get the blame, though they faithfully built what reached them. The actual loss was spread across every crossing upstream, where no single hop looked culpable — so the post-mortem indicts the last competent person in a chain of competent people.

Worst of all, it is misdiagnosed as a people problem, and the fix makes it worse. Because both sides were competent, the failure reads as carelessness — they should have written it down better, they should have asked — and the response is to demand more thorough handovers: longer specs, more detailed tickets, more handover meetings. But adding volume to a lossy channel does not fix the loss. It buries the load-bearing context deeper in noise and makes the next handover slower and less likely to surface the one thing that mattered. The instinctive fix treats the symptom and feeds the disease.

## How To Counter It
- **Widen the channel for the work that warrants it, and accept you cannot widen it for everything.** Triage handoffs. A routine transfer survives a thin artefact; a high-context, high-stakes one needs a richer channel — a real conversation, a period of overlap, pairing, shadowing. Match bandwidth to context depth deliberately, instead of running everything through the same fifteen-minute funnel.
- **Make the receiver read it back.** The cheapest way to find what was lost is to have the receiver state, in their own words, what they understood and what they intend to do — then the sender hears the gap between what they meant and what landed, while it is still cheap to close.
- **Hand over the why, not just the what.** Instructions survive compression; intent does not — yet intent is what lets a receiver handle the cases the instructions never anticipated. Transfer the reasoning and they can reconstruct the rest; transfer only the steps and they cannot.
- **Reduce the number of hops.** Every crossing is a lossy translation, so a chain of five handoffs loses more than a chain of two. Where the stakes justify it, let the originating expert talk directly to the final builder rather than relaying through three intermediaries who each re-compress.
- **Build overlap, not just transfer.** A clean instantaneous handoff is the lossiest design there is. A period where sender and receiver hold the work together — a few minutes of overlap on the ward, a sprint of shared ownership — lets tacit knowledge move through proximity, which is the only way most tacit knowledge ever moves.
- **Treat "the handover happened" as a question, not an answer.** Done is not when the ritual completed. Done is when the receiver can act correctly on the cases the sender never explicitly mentioned. Until then the channel has carried the summary, not the work.

## What Good Looks Like
A place that treats handoffs as the high-risk events they are, rather than as administrative formalities. Boundaries are still owned cleanly on both sides — division of labour is not the enemy and is not abandoned. What changes is that the crossing is designed instead of assumed: the channel is sized to the work, the why travels with the what, and the receiver's understanding is checked rather than presumed.

The richest, most consequential transfers get the richest channels — conversation, overlap, pairing — and the routine ones are allowed to stay thin, so attention goes where the loss would actually hurt. "The handover happened" is no longer taken as proof the work crossed intact; "can the receiver now handle what I did not spell out?" is the real test, and people apply it. When something arrives almost-right, the instinct is to ask what was lost in the transfer rather than who was careless — so the channel gets fixed instead of a person getting blamed, and the next handoff is better instead of merely longer.

In a place like that, work that is whole inside one team has a fighting chance of arriving whole inside the next — because someone designed the doorway to be as wide as the work, instead of hoping the work would fold itself thin enough to fit.

## A Reflective Question
Think of the last piece of work you handed to someone else — a brief, a ticket, a verbal handover. What did you know about it that never made it into what you passed on, because there was no time, no field for it, or no words for it yet? And if that one unspoken thing turned out to be the thing that mattered, who would get the blame — you, or the person who faithfully built what actually reached them?
