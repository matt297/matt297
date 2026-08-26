# Things I like building 🛠️

I'm a backend engineer at heart, with a particular soft spot for **Ruby on Rails**.

But I'm less interested in technologies as an identity and more interested in the problems they let us solve.

## Rails

Rails gives engineers a lot of useful building blocks and healthy defaults.

I like frameworks that take care of the boring-but-important fundamentals so that engineers can spend more energy on the genuinely hard problems.

One tiny example I love:

```ruby
User.where(email: email).sole
```

`.sole` doesn't just retrieve a record. It encodes an assumption:

> **There should be exactly one.**

If that assumption isn't true, the application should know about it.

That sort of thing captures a lot of what I like about Rails: sensible defaults that make it easier to express what you actually mean and harder to quietly do the wrong thing.

## APIs & SDKs

I spend a lot of time working with APIs, integrations, and developer experiences at scale.

I think a good API should be:

- predictable
- intuitive
- internally consistent
- built around coherent concepts
- realistic to maintain

That last one gets overlooked.

An API has two sets of users: the people consuming it and the folks building and supporting it.

The best API isn't necessarily the one with the most features or the most generous backwards-compatibility policy. It's the one that finds a sustainable balance between consumer experience, business needs, and engineering capacity.

I'm also cautious about exposing concepts before they've settled.

> **An API is a contract. Don't publish a thought experiment as one.**

## Everything is an interface

I work mostly on backend systems, but I care a lot about UX.

To me, a controller parameter, an API response, an SDK method, and a button on a screen are all versions of the same fundamental problem:

> **Someone is trying to accomplish something through an interface.**

That means many of the same principles apply:

- predictable behaviour
- clear mental models
- sensible defaults
- consistency
- meeting expectations

Good API design and good UX aren't the same discipline, but the mental models are remarkably similar.

## Scale changes the questions

Working at scale teaches you that your assumptions are probably wrong.

You can't design a system that's perfectly optimized for every possible use case. You have to understand the business, the system, the users, and the trade-offs well enough to know what deserves attention.

Sometimes that means building something robust enough for the 99th percentile while consciously accepting a trade-off for everyone else.

That's not cutting corners.

> **That's making an engineering decision.**

## What I enjoy most

Give me a problem where I need to:

- understand a messy business context
- figure out what people actually need
- design a system that can grow with that understanding
- make trade-offs between competing constraints
- find the right abstraction
- obsess over the name of an API field

I'll happily spend an unreasonable amount of time on it.

I'm less excited by work where the solution is mostly mechanical and there's little room to think about the bigger picture.

That's probably why I keep ending up somewhere around the intersection of **product thinking, systems, and code**.