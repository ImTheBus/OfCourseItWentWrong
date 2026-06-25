---
title: "The Customer Sees It Last, and Worst"
slug: the-customer-sees-it-last-and-worst
book: of-course-it-went-wrong
category: "Organisations and systems"
order: 139
summary: "Every layer it passes through makes it bigger and quieter, until the customer meets all of it at once."
published: true
---

# The Customer Sees It Last, and Worst

**Category:** Organisations and systems
*Every layer it passes through makes it bigger and quieter, until the customer meets all of it at once.*

---

An engineer notices something during a routine release on a Friday afternoon. A change to how the checkout calculates tax behaves oddly on orders shipped outside the home country — intermittently, and only on a small fraction of international orders. They flag it in a channel: "probably worth a look, not a blocker." At this moment the problem is at its smallest, its cheapest, and its most visible. One engineer, one message, ten minutes to investigate.

The release lead, under pressure to ship before the weekend, reads "not a blocker" and ships. The flag is real but quiet; it competes with louder things and loses. Over the weekend, support gets a trickle of confused emails about wrong totals. The weekend agent, with no context and a queue to clear, issues goodwill refunds and tags each one "billing query — resolved." The pattern is invisible because every ticket is closed on its own. By Tuesday a team lead notices refunds are up, reads it as a seasonal blip, and does not escalate.

Three weeks later it surfaces as a thread of furious public reviews — *charged me twice the tax, took four emails to sort, never again* — and, the same week, a query from a payments partner about a spike in chargebacks. Now it is large, expensive, undeniable, and public. The fix is still the same ten-minute fix the engineer flagged on the Friday. Everything else — the refunds, the chargebacks, the reviews, the customers who quietly left — is the cost of how long it stayed quiet. The bug never grew. The silence around it did.

The customer was the only party in the whole chain with no incentive and no ability to absorb the problem. So the customer was the one place it finally had to be seen.

---

## The Principle
A problem's visibility and its size move in opposite directions as it travels outward. Near the source it is tiny but loud — one person can see exactly what it is. At the edge it is enormous but, until it actually surfaces, was silent, because every layer between source and customer had the means to dampen it — a workaround, a refund, a reassuring explanation, a *we'll catch it next sprint* — and the incentive to do that rather than raise an alarm.

The customer is special in only one respect: they are the first party in the chain who cannot absorb the problem and has no reason to keep it quiet. So the edge is not where the problem is worst by bad luck. It is where the problem becomes unabsorbable — which is the same thing as finally visible. Last and worst are not two facts. They are one fact seen from two angles: the customer sees it last *because* every internal layer could swallow it, and sees it worst *because* swallowing it is what let it grow.

The honest caveat: not every absorbed problem should have been escalated. Most small things genuinely are small, and an organisation that escalated everything would seize up. The trap is that the same damping that correctly handles the small things also hides the few that are not small at all.

## Why It Is Inevitable
Every internal layer can absorb, and is rewarded for absorbing. A workaround, a goodwill refund, a quiet patch, a reassuring word to a manager — each makes the problem go away locally, which is exactly what each layer is measured on. Tickets closed. Releases shipped. Escalations avoided. Surfacing a problem upward is costly and thankless; absorbing it is cheap and looks like competence. So the default at every layer is to swallow.

The problem also arrives at each layer already pre-shrunk. Each layer sees only its slice — one ticket, one odd metric, one Friday flag — never the whole. Nobody is lying. Each person is genuinely seeing a small thing, because the structure hands them a small thing. The aggregate exists nowhere inside the organisation; it exists only at the boundary the customer sits on.

The customer, meanwhile, has the opposite incentives and the opposite abilities. They cannot patch it, cannot refund themselves, cannot reassure themselves it is seasonal. And they have every reason to make noise — complain, churn, post the review. The organisation's damping machinery has no purchase at all on someone standing outside the organisation.

Finally, distance launders cause. By the time the problem surfaces externally, it is weeks and several hand-offs from the Friday flag, so it reads as a new, external problem — a review crisis, a chargeback issue — rather than the old, internal one it always was. The organisation meets its own three-week-old bug as a stranger.

## How It Shows Up
- A defect known internally for weeks becomes "real" only the day a customer names it in public.
- A pattern that was a dozen individually-closed support tickets surfaces all at once as a trend nobody inside had assembled.
- The first full picture of the problem is put together by an outsider — a customer, a journalist, a regulator, a partner — before anyone inside had it.
- Front-line staff who flagged it early and accurately, and were absorbed or overruled. "We did raise this."
- A fix that is small and unchanged from day one, dwarfed by the cleanup that grew around it.
- Post-incident language that treats the customer-facing event as the start of the problem rather than its arrival.
- The full bill of an external failure: the fault itself, plus refunds and returns, plus reputation, plus the customers who simply left and said nothing.

## Why It Causes Damage
The bill at the edge is the original fault plus everything that should have caught it. A problem fixed at the source costs the fix. The same problem at the customer costs the fix plus every layer of cleanup it accreted on the way out — and those layers, the refunds and support load and public response, usually dwarf the fix itself. The organisation pays for the fault once and for the silence many times over.

External failure also spends trust, and trust does not refund. An internal problem fixed internally costs effort. A problem the customer experiences costs belief — in the product, in the brand, in the next purchase. Trust is slow to build and does not come back at the rate it left. The customer who churns over a botched checkout was often won at real cost, and the failure writes off that acquisition silently. It compounds, too: each public failure makes the next one land harder.

The deepest damage is that the organisation learns the wrong lesson, because the problem is now wearing a disguise. Because the failure surfaced far from its source and in a different form, the post-mortem fixes the symptom at the edge — better review monitoring, a bigger weekend support rota, a chargeback dashboard — while the actual mechanism, a culture that absorbs and dampens early flags, survives untouched. If anything it is reinforced: now there is more machinery for catching things late. The organisation gets better and better at meeting its problems at the edge, and no better at all at surfacing them at the source. The pattern does not just repeat; it professionalises. An organisation that is brilliant at customer-facing damage control is often an organisation that has given up, structurally, on early surfacing — it has built a system optimised to see its problems last.

## How To Counter It
- **Make surfacing a small problem cost less than absorbing it.** Reward the early flag, by name, even when it turns out to be nothing. Where raising "probably not a blocker" is safe and cheap, things get caught while they are still cheap. The people nearest the source are usually right and routinely overridden.
- **Aggregate across layers deliberately.** No layer saw the whole because nobody was tasked with joining the slices. Someone has to look at support, releases, and refunds together; the trend only exists in the join.
- **Treat the customer as a detector you installed too far away.** If the customer is your first reliable signal that something is wrong, the real problem is not the fault — it is that your earliest internal detector fires later than your slowest external one. Move detection inward.
- **Trace every external failure back to its first internal sighting, and fix that.** The post-mortem question is not "how do we catch this kind of complaint faster?" It is "when did someone first see this, and what made it cheaper for them to absorb it than to surface it?"
- **Shorten the distance between source and edge.** Fewer hand-offs between the person who can see a problem and the person who can act on it means less laundering of cause and less room for damping.
- **Distrust a clean external face over a noisy internal one.** A team that surfaces lots of small problems internally is usually healthier than one whose customers never complain. The second may simply be better at silence.

## What Good Looks Like
An organisation where the customer is rarely the one to discover the problem — not because nothing goes wrong, but because the things that go wrong get loud while they are still small. Early flags are cheap to raise and visibly valued. Someone is joining the slices, so trends surface internally before they surface externally. Post-mortems chase the first internal sighting, not the customer-facing symptom. The distance between seeing and acting is short.

When something does reach a customer, it is treated as a genuine miss in the early-warning system, not just an event to clean up. The wins still happen; the difference is who sees the problems first. In a healthy system the customer is the last line of detection, almost never the first — and the organisation would be embarrassed, not surprised, to learn of its own problems from a review.

## A Reflective Question
The last time a customer told you about a problem — how long had someone inside already known, and what made it easier for them to absorb it than to raise it?
