---
title: "The Spherical Chicken Fallacy"
slug: the-spherical-chicken-fallacy
book: of-course-it-went-right
category: "Systems That Assume Reality"
order: 12
summary: "Systems designed for ideal conditions are fragile because humans are not ideal."
published: true
---

# The Spherical Chicken Fallacy

*Systems designed for ideal conditions are fragile because humans are not ideal.*

---

There is an old joke that physicists tell about themselves. A farmer asks a physicist to help him improve the egg yield from his hens, and after weeks of study the physicist returns with a triumphant result. "I have a solution," he says, "but it only works for a spherical chicken in a vacuum." The joke lands because the model is flawless and useless at the same time. Every difficult, important thing about a real chicken — its shape, its feathers, the air it moves through, the fact that it will not stand still — has been assumed away to make the maths tractable. What is left is elegant, internally consistent, and unable to survive contact with a single actual bird.

Consider, then, a company that decides to overhaul how it handles expense claims. The old process was a mess of paper and chasing, and the team that redesigns it does a genuinely thoughtful job. The new process is a thing of beauty. There is a clear policy document. There is a well-built form. Every step is logical, every field is justified, and the whole thing works perfectly — *provided* the person filing the claim has read the policy in full, kept every receipt, filed within the window, used the correct category, and is not, at the moment of filing, distracted, tired, travelling, or in any hurry. The designers, sensible people, tested it on themselves at their desks on a calm Tuesday morning, and it sailed through.

Then it meets a sales rep filing three weeks of receipts from an airport lounge on a Friday afternoon, half-attending, who has not read the policy because nobody reads policies, and the beautiful process produces a rejected claim, an annoyed employee, and a finance team now doing by hand the very chasing the system was meant to end. The process was not badly built. It was built for a spherical chicken — for an idealised user who does not exist — and it broke on the first real one. The systems that *don't* break are the ones built, from the start, for the real bird.

---

## The Principle
**Systems that last are designed for human beings as they actually are — busy, distracted, occasionally careless, working with partial attention — rather than for the idealised, perfectly compliant user the designer imagines while building. Robustness does not come from demanding that people behave ideally; it comes from assuming they won't, and working anyway.**

The seductive move, when designing any process, is to assume the user away. To assume they will read the instructions, follow the steps in order, remember the rule from last quarter, notice the small print, and bring full attention to a task that is, for them, a minor irritation in a busy day. This is not done out of arrogance, usually. It is done because the idealised user makes the system *simpler to design* — every assumption you make about the human is one fewer thing the system has to handle. The spherical chicken is appealing for exactly the reason it is wrong: it removes the messiness that was the whole problem. A system built on those assumptions can be beautiful, coherent and internally perfect, and still be fragile, because its robustness was borrowed entirely from the good behaviour of its users. The strongest systems borrow nothing. They assume the human will be at their worst — rushed, half-reading, mis-clicking — and they still produce a good outcome, because the work of handling that was done in the design rather than left to the person.

## Why It Is Inevitable
This is not a refinement that only the most enlightened designers reach. It is something that any system surviving real use is forced into, because the idealised user fails in a way that is not occasional but constant.

The first reason is that the idealised user simply does not exist, anywhere, ever. There is no population of people who read every email in full, follow every step in order, and bring undivided attention to administrative tasks. The compliant user is not rare — they are imaginary. A system designed for them is therefore designed for nobody, and the gap between the imagined human and every real one is not a tail risk that bites occasionally; it is the *normal operating condition*. The first real user reveals it, and so does the second, and the thousandth.

The second reason is that the cost of the gap is paid downstream, where it is most expensive. When a system assumes the human will behave perfectly and the human does not, the failure does not vanish — it lands somewhere. It lands on the finance team chasing the malformed claim, on the support queue handling the predictable confusion, on the colleague cleaning up the step that was skipped. A system that offloads its messiness onto its users does not eliminate that messiness. It relocates it to the people least equipped to absorb it, and they absorb it at the worst possible moment, by hand. So any process that runs at scale is pushed, by the sheer weight of that downstream cost, toward absorbing the messiness itself.

The third reason is that the world changes around the idealised assumptions and erodes them further. The policy gets updated and nobody re-reads it. A new cohort arrives who never saw the original instructions. The context shifts — people start filing from phones, from airports, between meetings — and every shift makes the real human a little further from the ideal one. A system that depended on ideal behaviour was decaying from the day it launched, because the conditions it assumed were never going to hold still. The systems that endure are the ones that never depended on those conditions in the first place. They were built for the real bird, so they survive the bird changing.

## How It Shows Up
- A process is tested by its designers, on themselves, in calm conditions — and never on a distracted person doing it for the first time at the end of a long week.
- The instructions are clear, complete, and correct, and the system quietly assumes they will be read. They will not be.
- The system has exactly one correct path, and any deviation — a skipped field, a wrong category, a late filing — produces failure rather than a graceful nudge back onto the path.
- Errors that are entirely predictable ("people will forget to attach the receipt") are treated as user mistakes to be corrected, rather than design conditions to be handled.
- When something goes wrong, the post-mortem reaches for "the user didn't follow the process" as a sufficient explanation, and stops there.
- The robustness of the whole thing rests, invisibly, on everyone behaving well — and nobody notices, because in the demo everybody did.

## Why It Causes Benefit
When a system is built for the real human rather than the ideal one, it gains a kind of robustness that cannot be bolted on afterwards. It stops being fragile in the specific, expensive way that idealised systems are fragile: it no longer breaks on contact with ordinary human imperfection, because ordinary human imperfection was the design brief.

The most immediate benefit is that the predictable failures simply stop happening. The receipt that always gets forgotten is now prompted for, or made optional, or captured a different way — so the malformed claim that used to clog the finance queue never arrives. The whole class of error that an idealised system generates as a matter of routine is designed out, which means the downstream people are not spending their days absorbing the consequences of an upstream assumption. The system that was supposed to save work actually saves it, because it stopped manufacturing the very mess it was meant to prevent.

There is a deeper benefit, too, in how such a system behaves under pressure. An idealised system is most fragile exactly when reality is hardest — when people are busiest, most distracted, most likely to cut corners — which is to say it fails most when it is needed most. A system built for the real human is the reverse: it was designed for the Friday-afternoon, half-attention, three-weeks-of-receipts case, so that case is the one it handles best. Its performance does not collapse when conditions degrade, because degraded conditions were the assumption. That is what robustness actually means — not that the system works in the demo, but that it keeps working when the humans are at their most human. And because it keeps working then, the trust people place in it is earned rather than borrowed; they stop dreading the process, stop building private workarounds, and start, quietly, relying on it. A system that survives the real bird gets *used*, and a system that gets used is the only kind that delivers the benefit it promised.

## How To Cultivate It
- Design for the worst realistic user, not the best imaginable one. Picture the specific person — rushed, half-reading, doing this for the first time on a phone between meetings — and build for *that* person. If the system works for them, it works for everyone; the reverse is not true.
- Treat predictable human behaviour as a design input, not a moral failing. "People won't read the policy" and "people will forget the receipt" are not complaints about users. They are facts about the world, as solid as gravity, and the system's job is to work despite them, not to wish them away.
- Test in real conditions, on real strangers, in the state they'll actually be in — tired, distracted, mildly resentful of the task — and not on the designers at their desks on a calm morning. The calm-Tuesday test is the spherical-chicken test, and it always passes; it tells you nothing.
- Make the correct path the easy path, and make deviations recoverable rather than fatal. A system with one narrow correct route is brittle; a system that gently catches and redirects the inevitable wrong turns is robust. Aim for graceful nudges, not hard rejections.
- Move the messiness into the design, not onto the people. Every assumption you make about good user behaviour is a fragility you have introduced. Hunt those assumptions down and ask, for each one, "and what happens when this isn't true?" — then handle that case in the system rather than leaving it for a human to absorb downstream.
- When something fails, resist "the user didn't follow the process" as an explanation. It is almost always true and almost never useful. The useful question is why the system permitted, or even invited, the deviation — and what design change would have absorbed it.

## What Good Looks Like
A system you can hand to a distracted person on a Friday afternoon and trust to produce a good outcome anyway. The correct path is the path of least resistance, so people fall onto it without effort; the predictable mistakes are caught and redirected gently rather than rejected coldly; and the whole thing was tested not on its calm, careful designers but on the rushed, half-attending humans who will actually use it. Nothing about it depends on anyone reading the policy, remembering the rule, or bringing their full attention to a task they regard as a chore — because all of that messiness was absorbed in the design, where it cost the designer some effort once, rather than offloaded onto every user and every downstream colleague, where it costs everyone effort forever. The system is, as a result, robust in the only way that matters: it works best precisely when conditions are worst, because the worst conditions were what it was built for. It does not assume the spherical chicken. It was designed, from the first sketch, for a real and imperfect bird — and that is exactly why it does not break.

## A Reflective Question
Think of a process you rely on that works beautifully in the demo. Now picture the most distracted, rushed, half-attending version of the person who actually uses it, on their worst day — and ask honestly whether the process is built to survive that person, or whether it is quietly depending on them to behave like someone who does not exist.
