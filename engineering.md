# How I think about engineering 🧠

I like solving hard technical problems. But before I start solving one, I want to understand **what we're actually trying to accomplish**.

All software exists to serve some kind of business or product outcome, and that context should shape the system we're building.

## Start with the why

My mental model is roughly:

**Business need → system requirements → architecture → implementation**

The code is often the last step.

Some questions I like asking early:

> **Why are we doing this?**

> **How will we know what good enough looks and feels like?**

> **How will we know if we succeeded?**

Understanding the goal often makes the technical problem easier. Sometimes it tells us what we *don't* need to build. Sometimes it reveals that we should design for something the business expects to do later. And sometimes it tells us that the right answer is to build something deliberately temporary.

## Complexity should earn its keep

Complexity for the sake of complexity is dumb.

I prefer simple designs and letting abstractions emerge as we learn more, rather than trying to predict every possible future requirement up front.

That doesn't mean avoiding sophisticated systems. It means being able to explain **why the sophistication exists**.

I think systems are easiest to reason about when they're predictable and follow shared conceptual patterns. A team using the same framework doesn't necessarily mean everyone has the same mental model.

Shared understanding matters more than shared syntax.

## Prototypes are for learning

I'm very much in favour of prototypes.

I'm also very much in favour of throwing them away.

Code, mockups, experiments, and AI-generated prototypes can all be excellent ways to explore a problem. But an implementation we created to learn something shouldn't automatically become the architecture we're stuck with.

**A prototype is evidence, not a commitment.**

## Ship, observe, learn

One of my stronger opinions:

> **Ship early and often to learn.**

Especially at scale, you're going to get things wrong. Assumptions need validation, and there is no perfect system that optimizes for every possible use case.

The goal isn't to eliminate uncertainty before shipping. It's to understand which uncertainty matters, make sensible trade-offs, and learn from reality.

Sometimes the best architecture is the one that gives us enough confidence to take the next step — not the one that tries to predict the next ten.

## Documentation is about understanding

I care a lot about documentation, but not documentation for its own sake.

If the code explains something clearly, read the code.

What I want documented is the context that the code can't easily provide:

- Why does this work this way?
- What trade-off did we make?
- What assumption are we relying on?
- Why isn't the obvious alternative appropriate?

**Documentation is a tool for creating shared understanding.**

That also means it needs to be maintainable and actually readable. A beautifully written document that's six months out of date isn't particularly useful.

## AI is a tool, not the point

I'm very much on board with AI-assisted or even AI-driven development. I use it to explore ideas, prototype, understand unfamiliar systems, and reduce tedious work.

But generating code isn't the interesting part of engineering.

The interesting part is figuring out **what should exist, why it should exist, and whether it actually solves the problem**.

That's where I still want engineers thinking.