---
title: "Problems Don't Stay in Their Lane"
slug: problems-dont-stay-in-their-lane
book: of-course-it-went-wrong
category: "Organisations and systems"
order: 128
summary: "Issues spread across boundaries whether allowed or not."
published: true
---

# Problems Don't Stay in Their Lane

**Category:** Organisations and systems
*Issues spread across boundaries whether allowed or not.*

---

A single supplier in a tier-three factory misses a shipment of a small electronic component. It is not a dramatic failure. A storm closed a port, a container sat for three days, and a part worth a few pence per unit arrived late. On the org chart, this is a procurement issue, owned by a procurement manager, sitting in a procurement spreadsheet under a heading that says "minor delay, monitoring."

Six weeks later the problem surfaces in a place no procurement spreadsheet reaches. The assembly line that needed the part has been running on a workaround, substituting a near-equivalent that nobody fully tested under load. Field units start failing in a way that looks like a software fault, so the software team gets the ticket. They spend a fortnight chasing a bug that is not in their code. Meanwhile the sales team, who knew none of this, has promised a delivery date that now cannot be met, and the account manager is on the phone to a furious customer explaining a failure he has never heard the cause of and could not have prevented.

Ask each person in that chain whose problem this is, and every one of them will tell you, accurately, that it is not theirs. The procurement manager closed a late shipment. The line manager kept the line running. The software team fixed the tickets in front of them. The account manager honoured the date he was given. Nobody dropped a ball. The ball simply rolled across four boundaries that the org chart drew as walls, and it came to rest on a desk belonging to someone who had no part in dropping it.

That is the whole pattern, and once you have seen it you will see it everywhere: a problem is born inside one neat box, and it is felt inside a completely different one.

---

## The Principle
**A failure contained in one part of a system does not stay contained. It travels along the real connections between parts — which are denser and messier than the formal boundaries suggest — and surfaces somewhere unrelated, unprepared, and unowned.**

The org chart is a map of authority, not a map of how the work actually flows. It tells you who reports to whom. It does not tell you that the warehouse, the website, the finance close, and the customer's experience are all wired to the same underlying truth, so a disturbance in one will eventually register in the others.

Boundaries on a diagram are clean lines. Boundaries in a working system are leaky membranes. Pressure on one side raises pressure on the other, even when no one signed up for that, and even when the line on the chart looks solid enough to lean on.

## Why It Is Inevitable
Parts of a system are coupled whether or not anyone designed them to be. They share inputs, they share infrastructure, they share people, they share the same finite pool of time and attention. A problem in one part consumes some of that shared resource — a workaround, a delay, an extra reconciliation, a person pulled off their own job to firefight — and the shortfall propagates to whatever was relying on the resource that just got eaten.

Under light load, the slack absorbs it. There is spare capacity, spare time, spare goodwill, and a local problem stays local because the system has room to soak it up before it reaches a boundary. This is why clean boundaries look real most of the time: most of the time there is enough slack that nothing crosses, and we mistake "absorbed by spare capacity" for "contained by design."

Under load, the slack is gone. Now every part is running close to its limit, every buffer is thin, and a disturbance that would once have been quietly absorbed instead pushes straight through to the next part, and the next, because there is no give left anywhere to stop it. The boundary did not change. The slack that was doing the real containment disappeared, and the boundary was revealed to have been holding nothing.

And the failure travels furthest along the connections nobody documented. We map and defend the formal interfaces. The informal ones — the verbal agreement, the shared spreadsheet, the one person who happens to know how two systems fit together — are where the problem actually flows, precisely because no one is watching a connection they never wrote down.

## How It Shows Up
- A "small local issue" is logged and closed in one team, and weeks later an apparently unrelated failure appears in another.
- The team that feels the symptom has no authority over the cause, and the team that owns the cause never feels the symptom.
- A problem is handed around several departments, each correctly establishing that it is not theirs, while it remains unfixed.
- The most expensive failures consistently happen at the seams between functions, not inside any one of them.
- Everyone's own area is "green," and yet something is plainly going wrong across the whole.
- The investigation spends days in the wrong department because the symptom surfaced far from its origin.

## Why It Causes Damage
The first cost is misdiagnosis. The problem surfaces a long way from its source, so the people who feel it look for the cause where they feel it — in their own code, their own process, their own team — and they will not find it there. Effort, sometimes a great deal of it, is spent treating the place the problem landed rather than the place it came from. The symptom is real, the urgency is real, and the search is pointed in the wrong direction.

The second cost is that nobody owns it. Because the problem crosses boundaries, it falls into the gaps between owners, and gaps have no defender. Each party can prove they did their job. The thing that is failing is the connection between their jobs, and connections rarely appear on anyone's objectives. So the problem persists, not because it is hard to fix, but because no single person has both the authority to fix it and the experience of the pain that would motivate them to.

The third cost is that the denial hardens. The cleaner an organisation believes its boundaries are, the more it treats cross-boundary failures as anomalies — bad luck, one-offs, somebody else's mess — rather than as the predictable behaviour of a coupled system under load. It keeps drawing walls where there are membranes, and keeps being surprised, in exactly the same way, by exactly the same kind of leak.

## How To Counter It
- Map the system by how the work flows, not by who reports to whom. Find the real connections — the shared resources, the informal hand-offs, the single points everything routes through — and treat those, not the org chart, as the boundaries that matter.
- Watch the seams. The interfaces between teams are where problems cross and where no one is measured, so make the hand-offs explicitly someone's responsibility rather than no-man's-land.
- When a problem surfaces, ask "where could this have come from?" before "how do we fix it here?" Trace it upstream across boundaries before you spend effort treating it where it landed.
- Assume spillover and design for it. Build in the buffers, the back-pressure signals, and the escalation paths that let one part tell another it is in trouble *before* the failure arrives unannounced.
- Give cross-boundary problems a single named owner with the authority to reach across the lines. The thing that has no defender needs one appointed, because it will not appoint itself.
- Be most alert when the system is under load. That is precisely when the slack that was silently containing everything runs out and the boundaries stop holding.

## What Good Looks Like
Organisations that treat their boundaries as porous and plan accordingly. Where a late shipment in procurement automatically raises a flag visible to the line, the software team, and the account manager, so the problem is tracked across the system rather than closed inside one box. Where the seams between functions have owners, the hand-offs are tested, and the question "what does this do to everyone downstream?" is asked as a matter of routine rather than after the damage.

Where, when a failure surfaces, the first instinct is to trace it back across the lines rather than to fix it where it appeared — and where the people who feel a symptom they did not cause are met with curiosity about the source rather than a chorus of "not my department."

The boundaries still exist. They are just understood for what they are: useful lines for assigning authority, and useless walls for stopping problems. Good systems stop pretending the second thing is true and start designing for the world in which it isn't.

## A Reflective Question
Think of the last problem that blindsided your team — the one that arrived from nowhere and felt like none of your doing. If you trace it back across every boundary it crossed, where did it actually begin, and who could have seen it coming if anyone had been watching the space between the lines?
