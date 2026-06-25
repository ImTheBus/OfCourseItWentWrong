---
title: "Scale Changes Everything"
slug: scale-changes-everything
book: of-course-it-went-wrong
category: "Organisations and systems"
order: 131
summary: "Practices that work small often fail when enlarged."
published: true
---

# Scale Changes Everything

**Category:** Organisations and systems
*Practices that work small often fail when enlarged.*

---

A small restaurant runs beautifully. The owner is in the kitchen, the same two people have worked front of house for years, and when something goes wrong, everyone knows because they can all see the room. Standards stay high without anyone writing them down. They are held in people's heads and enforced by the simple fact that the owner is standing right there, tasting the food.

It works so well that they open a second site. Then a third. Then they are a small chain, and the owner cannot be in every kitchen. The things that kept the first restaurant good — his eye, the shared instinct of a tiny team, the fact that everyone could see everything — do not exist at the new sites, because those things were never really a system. They were a side effect of being small.

So the standards drift, site by site, in ways nobody intends. Each new manager does their reasonable best with what they were given, which was a recipe and a brand but not the thing that actually made the original work. The owner, baffled, says the new sites just need to "do what we've always done." But what they had always done was be a place small enough to run on instinct, and that is the one thing they can no longer be.

The food gets worse not because anyone got worse, but because the model that produced it quietly stopped applying the moment it grew.

Watch the same thing happen somewhere with no kitchen in it at all. A two-person software team ships fast and rarely breaks anything. They do not have a release process; they have a sense of what the other one is touching, because they sit close enough to say "don't deploy, I'm mid-thing" out loud. They do not write much down; they remember. They do not test exhaustively; one of them simply knows which corners are fragile. It is a beautiful, fast little machine, and its speed gets it noticed, and it grows. By the time there are fifteen engineers, nothing in that paragraph survives. Nobody can hear who is mid-thing. Nobody remembers all the fragile corners; the person who knew them is now in meetings. The "process" was two people and a shared field of view, and you cannot hire your way to a shared field of view — fifteen people do not have one, and cannot, no matter how good they are. The bugs that arrive are not a competence problem. They are the sound of a method that was never a method, breaking exactly where its invisible support — proximity — used to be.

---

## The Principle
**A practice that works at one size is not a smaller version of the same practice at a larger size. Scale is not "more of the same" — it changes the nature of the thing, and methods that depended on smallness fail silently when smallness goes.**

Many things that work do so because they are small, even though nobody notices that smallness is doing the work. Direct oversight, shared context, informal coordination, one person holding the whole picture — these are not strategies that happen to scale poorly. They are properties of being small, and they vanish the moment you are not.

## Why It Is Inevitable
The thing that worked at small scale appeared to be a method, so the natural move when growing is to keep the method and just do more of it. But the method was leaning on invisible supports — the founder's attention, a team small enough to talk without process, a problem small enough to hold in one head. Those supports were never written into the method because nobody knew they were there. They were just the water everyone swam in.

Growth removes them one at a time, and removes them quietly. There is no point at which an alarm sounds to say "you are now too big for everyone to simply know what is going on." The breakdown is gradual and looks, from the inside, like a slipping of standards or a failure of the new people — anything but what it actually is, which is a model being asked to do a job it was never built for.

There are really three separate things failing at once here, which is part of why the failure is so hard to name while it is happening. The first is **oversight**: a single pair of eyes that could see the whole now cannot, and nothing has replaced it, so quality stops being watched and starts only being hoped for. The second is **shared context**: when everyone could see everything, coordination was free — it happened in the act of being in the same room — and once they cannot, that same coordination has to be manufactured deliberately, at cost, and it is never quite as good. The third is **tacit knowledge**: the standard that lived in one person's instinct was never made explicit, because it never needed to be, and so it cannot be copied to a new site — it can only be lost. Each of these decays on its own schedule, so the organisation never gets one clean signal that the model has broken. It gets three slow, separate degradations that each look like an ordinary problem, and it treats them as three ordinary problems, and misses that they are one structural one.

It is also genuinely hard to know in advance which of your strengths are real and transferable and which are just artefacts of your size. You usually only find out by scaling and watching which ones break.

## How It Shows Up
- "It used to just work" — said about a process that has not changed, in an organisation that has grown.
- Founders or veterans frustrated that newcomers "don't get it," when the thing to get was never made explicit.
- Coordination that used to happen in a corridor now needs three meetings and still goes wrong.
- Quality that was uniform when small becomes wildly variable across sites, teams, or regions.
- Heroic individual effort papering over the gap, working harder to manually supply what smallness used to supply for free.

## Why It Causes Damage
The organisation grows on the assumption that it is replicating its success, when it is often replicating only the visible shell of it. Resources go into more sites, more staff, more volume — all of which amplify the now-broken model rather than fixing it. You do not just fail to get bigger-and-as-good; you get bigger-and-worse, and at greater cost.

It also damages the people. Newcomers are blamed for not reproducing a magic they were never handed, and veterans burn out trying to be everywhere at once, manually holding together what used to hold together by itself. The failure gets read as a people problem and "solved" with more hiring and more pressure, which makes it worse.

## How To Counter It
- Before scaling, ask which of your strengths are methods and which are artefacts of being small. Assume more of them are artefacts than you think.
- Make the invisible supports explicit. If the founder's eye is what kept quality high, build the thing that does that job when the founder cannot — and accept it will be different, not identical.
- Expect the model to change shape, not just size. Doing "the same thing, bigger" is usually the error; the real task is designing a new thing that produces the same outcome at the new scale.
- Scale in steps you can observe, so you can see what breaks while it is still small enough to fix.
- Watch for heroics. When individuals are working unsustainably hard to keep standards up, that is the sound of a model that no longer fits, not a virtue to celebrate.

## What Good Looks Like
Organisations that grow deliberately, treating each jump in size as a redesign rather than a copy. That ask honestly what was carrying the original success and build explicit replacements for the parts that were only ever free because they were small. That measure whether the outcome survives the scaling, not just whether the activity has been reproduced.

They end up larger and still good — not because they kept doing the same thing, but because they understood that the same thing, at a different size, is a different thing.

There is a related failure that is easy to mistake for this one, and the difference is worth being exact about. This chapter is about what happens to *a method* when smallness is removed — the supports it leaned on disappear, and it stops producing its old result. The neighbouring failure is about what happens to *coordination itself* as people are added: the cost of keeping everyone aligned does not just grow, it grows faster than the headcount, until a group spends more effort syncing than the work would ever have taken. The two are cousins, but they point in opposite directions for the fix. The scale problem is solved by *redesigning the method* so it no longer needs the smallness it lost — building real oversight, explicit standards, deliberate context-sharing. The coordination problem is solved by *adding fewer people*, not more — because there, every extra person is part of the disease rather than the cure. Scale changing everything tells you the old way will break when you grow; coordination cost tells you that throwing people at the break will often make it worse. Confuse them and you will respond to a broken method by adding bodies, and to a coordination tax by demanding better process from a group that simply has too many members to ever be cheap to coordinate.

## A Reflective Question
Think about something in your world that works well today. How much of why it works is the method itself — and how much is simply that it is small enough not to need one?
