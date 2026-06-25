---
title: "Tools Outgrow Their Purpose"
slug: tools-outgrow-their-purpose
book: of-course-it-went-wrong
category: "Organisations and systems"
order: 152
summary: "Tools shape behaviour long after they should be retired."
published: true
---

# Tools Outgrow Their Purpose

**Category:** Organisations and systems
*Tools shape behaviour long after they should be retired.*

---

A small company needs to share a few documents between two offices, so somebody sets up a shared drive. It takes an afternoon. It solves the problem completely. The two offices can now see each other's files, and for a year nobody thinks about it again, which is exactly what you want from a tool — for it to disappear into the work and stop being a topic.

Then it stops disappearing. Finance starts keeping the master spreadsheet there because that is where everyone looks. Someone builds a folder structure that the warehouse depends on, because a script they wrote reads files out of a particular path. A new hire is told, on day one, "everything important is on the drive," and treats that as a law of nature rather than a decision somebody once made on a slow afternoon. The drive is no longer holding a few documents between two offices. It is holding the spreadsheet the month-end close runs on, the folder layout three automations assume, and the institutional belief that this is simply where things live. It has accreted.

And now ask the obvious question — should we move to something better? — and watch the room go quiet. Because the honest answer is that nobody fully knows what depends on it. The drive was set up for one thing, but it has been load-bearing for a dozen others for so long that pulling it out feels less like an upgrade and more like surgery on a patient whose anatomy nobody has mapped. So it stays. It stays not because it is good, but because it is *known*, and because the cost of leaving is now made entirely of unknowns. The tool has outgrown its purpose, and in doing so it has made itself almost impossible to retire.

You can find this shape under almost any tool that has been around for a while. The spreadsheet that started as one person's tracker and is now the system of record for a whole department, run by macros nobody living understands. The internal tool a clever engineer built one quarter to solve a real annoyance, which is now wired into six other things and the engineer left two years ago. The naming convention, the email distribution list, the shared inbox, the bit of middleware that everything routes through "for historical reasons." None of them were mistakes. Each was a sensible answer to a real problem. What went wrong is not that they were chosen — it is that they were never *un*-chosen, and a tool that is never retired does not politely hold its original scope. It expands to fill whatever it touches, and then it starts to charge rent.

---

## The Principle
**A tool is adopted to solve one bounded problem, but it does not stay bounded. It accumulates uses, dependencies, and expectations it was never designed for, until it constrains the very work it was meant to enable — and the more it has accumulated, the riskier removing it becomes, so the worse it gets to keep, the harder it is to leave.**

The trap is structural, not a matter of anyone being lazy or sentimental. A tool that works gets used. Being used, it gets used for adjacent things, then for things further out, then for things it was actively unsuited to, simply because it was *there* and already trusted. Every one of those uses lays down a dependency. And dependencies are not symmetrical with the original choice: adopting the tool took an afternoon, but each new thing that comes to rely on it raises the cost of ever removing it — quietly, cumulatively, with no single moment where anyone signs off on the growing liability. The decision to keep is never made. It is defaulted to, every day, by the simple fact that leaving has become expensive and staying is free until it isn't.

## Why It Is Inevitable
Start with the thing that makes it begin: a tool that solves its problem well is *invisible*, and invisibility is the goal. You do not want to think about your shared drive any more than you want to think about your plumbing. But invisibility and scrutiny are opposites. The better a tool works, the less anyone looks at it, and the less anyone looks at it, the more freely it can sprawl into roles nobody ever evaluated it for. Success buys it immunity from review. The tools most overdue for retirement are precisely the ones that have been reliable longest, because reliability is what stopped anyone from ever questioning them.

Then there is the asymmetry of accretion. Adding a use to an existing tool is nearly free — it is already there, already trusted, already learned. Building or buying the *right* tool for that new use costs money, time, and the friction of getting people to adopt something new. So at every individual decision point, "just put it on the drive" or "just add a column to the spreadsheet" is the rational, frugal, sensible choice. Each accretion is locally correct. It is only the *sum* of a hundred locally correct accretions that produces a tool doing twelve jobs it was designed for none of — and nobody ever made the decision to build that thing, because it was never one decision. It was a hundred small reasonable ones, and you cannot point at the moment it went wrong because there wasn't one.

There is also a human attachment that hardens the structural trap. People learn tools. They build skill, fluency, mental models, and a quiet pride in knowing where everything is and how to make the awkward thing work. A proposal to replace the tool is heard, not unreasonably, as a proposal to throw away that hard-won fluency and make everyone a novice again. The person who knows the spreadsheet's macros is, in a real sense, *powered* by the spreadsheet's complexity; simplify it and you diminish them. So the people best placed to explain why a tool should be retired are often the very people whose standing depends on it not being.

And the deepest reason is the one the chapter is named for: the dependencies are not visible until you pull. The whole point of a dependency is that it works silently — you do not notice that month-end reads from a particular folder until you move the folder and month-end breaks. So the true cost of removal is never known in advance. It is only discovered, painfully, during the removal itself. This makes the risk of leaving feel unbounded and the risk of staying feel like zero, which is exactly the asymmetry that keeps bad tools alive. You are not choosing between a known cost and a known benefit. You are choosing between a comfortable known and a frightening unknown, and humans default to the known almost every time.

## How It Shows Up
- "We can't change that — too much depends on it," said by people who cannot actually list what depends on it.
- A tool adopted for one job is now described as "the system of record" for several, none of which it was designed to be.
- New joiners are taught the tool's quirks as fixed facts of the world, not as the workarounds for an old decision they are.
- The person who understands the tool's accumulated complexity is treated as indispensable — and is, which is the problem.
- Every proposal to replace it stalls on the same question — "but what would break?" — that nobody is funded to actually answer.
- The tool is now a reason work is done a certain way, rather than a means of doing the work the way you'd choose.
- A migration has been "on the roadmap" for three years and slips every time, because the cost of leaving is real and the cost of staying is invisible.

## Why It Causes Damage
The first damage is the obvious one: the tool starts constraining the work it was meant to serve. The shape of what is possible gets quietly bent to fit what the tool can do. New ideas are pre-rejected — not after consideration, but reflexively — because "that won't work with the drive," and so the tool stops being a means and becomes a boundary on the imagination. You are no longer using the tool to do the work; you are doing the work the tool allows. The tail has been wagging the dog for so long that people have forgotten there was ever a dog.

The second damage is fragility, and it is worse because it is hidden. A tool with a hundred undocumented dependencies is a single point of failure that nobody has dared map. It works, reliably, right up until it doesn't — and when it doesn't, the failure cascades through dependencies nobody knew existed, in an order nobody can predict, at a moment nobody chose. The same invisibility that let it sprawl is what makes its eventual failure unsurvivably surprising. And because the knowledge of how it actually works has concentrated in one or two people, the organisation is exposed to those people leaving, or being on holiday, or simply forgetting — a risk that compounds quietly every year the tool is kept.

The third damage is the cruellest, because it is paid in the currency the tool was supposed to save: the cost of *staying* eventually exceeds the cost of *leaving*, and you go on paying it anyway. Every workaround, every "you just have to know," every hour spent maintaining a thing past its usefulness, every good idea quietly abandoned because the tool couldn't take it — these are real costs, but they arrive in small, deniable instalments that never trigger a decision. The removal cost, by contrast, arrives all at once, visibly, with someone's name on it. So an organisation will rationally pay far more, in total, to avoid a smaller cost it would have to pay *deliberately*. It is not that keeping the tool is cheap. It is that keeping it never requires anyone to stand up and own the expense, and so the expense is borne forever in the dark.

## How To Counter It
- Map the dependencies *before* you need to. The reason removal feels unboundedly risky is that nobody has done the unglamorous work of writing down what actually relies on the tool. Fund that work as standalone work — an audit, deliberately, while the tool is still healthy — and you convert a frightening unknown into a manageable list.
- Periodically ask the founding question again: what problem did we adopt this for, and is that still the problem we have? A tool kept past the death of its original purpose is the surest sign that scope has drifted while the tool stood still.
- Treat new uses as decisions, not conveniences. The instinct to "just put it on the drive" is where accretion begins. Make adding a load-bearing use to an existing tool a thing someone has to actually choose, with the dependency it creates named out loud, rather than a thing that happens by default because the tool was nearby.
- Separate the cost of staying from the cost of leaving, and make the first one visible. Tally the workarounds, the bus-factor risk, the ideas the tool has vetoed. The point is to drag the standing cost of keeping into the light, where it can be compared honestly against the one-off cost of going.
- Retire deliberately, in daylight, not in a crisis. The worst time to remove a tool is the moment it finally breaks — under pressure, blind, with dependencies revealing themselves as failures. Plan the retirement while the tool still works, run the replacement in parallel, and migrate the dependencies one at a time with each one understood before it moves.
- Distribute the knowledge before you distribute the tool. If one person understands the accumulated complexity, the retirement risk lives in their head. Getting that knowledge out of one head and into a shared, written form is not just good for the migration — it is the thing that makes the migration thinkable at all.

## What Good Looks Like
Organisations that hold their tools loosely — useful while they fit the problem, and retired without drama when they stop. Where the dependencies a tool has accumulated are written down and known, so that "what would break?" has an answer rather than a shudder. Where adopting a tool comes with a quiet expectation that it will one day be replaced, and the architecture is kept honest enough that replacement is a project, not an excavation.

It does not mean churning through tools, or treating every reliable thing as suspect — that is its own waste. It means keeping the original purpose of a tool in view, noticing when the tool has drifted off it, and being willing to do the deliberate, unglamorous work of leaving *before* the cost of staying has been paid for years in the dark. The tool was always meant to serve the work. The discipline is simply to remember that, and to retire the tool the moment it forgets.

## A Reflective Question
Look at the tool your work most depends on. If it vanished tomorrow, do you actually know everything that would break — or is the real reason you keep it not that it still serves you, but that nobody has mapped what it would cost to leave?
