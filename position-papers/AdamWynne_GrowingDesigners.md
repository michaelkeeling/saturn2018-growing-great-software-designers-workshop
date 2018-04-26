# How to move from art to science?

## Introduction

We are a large multi-national engineering company who is undergoing a "digital
transformation," moving from selling "things" to services coupled with
network-enabled devices. Our division is at the forefront of this effort,
running multiple agile teams who are fully invested in devops and deploying
continuously to the cloud while IT tries to keep up.  I am part of a team that
is a kind of "internal startup" where the business side is moving fast, causing
us to incur some significant technical debt.  In the past we have given into the
"temptations of easy wins." 

## Some Challenges

In general the challenges I see are related to integrating design thinking into
the agile development process. This is challenging on its own but additionally
there is often a need to simultaneously coach for these skills while coming up
with the right process to practice them. Specifically:

* Many new and experienced developers have never practiced reading and writing
  design documents. This makes it hard to get started with design practices
  given the every day demands and pressures of the sprint.
* Some don't see the need and/or don't see how design activities can fit into
  an agile development process. 
* The agile context is used to justify quick solutions and to ignore risks that
  aren't immediately apparent.
* Getting team members up to speed quickly on how to do quality design, while
  enabling them to produce visible output in each sprint 
* Finding the right balance between closely guiding agile team members on the
  one hand and enabling them to learn from their own mistakes on the other.
  The latter is required to become empowered agile practitioners.

## Needs 

The needs can be distilled to tools and concrete practices that embody deep
principles while being easy to pick up and have a clear mapping to a typical
agile methodology. For example:

* Lightweight design notations and tools that are easy to learn and fit into
  the "everything is code" mindset while being comprehensive enough to grow
  with the team and product.  I'm thinking of something as visually intuitive
  as Simon Brown's ["Architecture for
  Developers"](https://leanpub.com/b/software-architecture) that has the
  maintainability and standardized nature of [PlantUml's](http://plantuml.com)
  textual DSL while having a limited number of symbols like the notation
  from SEI's microservices training. Any language that is too expressive has
  the capability to be abused, misunderstood, and a time-suck. Yes there a many
  things to choose from but none seem to scratch all these itches at the same
  time.
* Practices to help quickly (iteratively?) get team members up to speed on how
  to read and write graphical notations.
* Concrete guidance on how to coach teams to do some kind of rapid trade off
  analysis. For example, given a feature on short deadline that clearly has
  impact on software qualities, how can we get the whole team to sort out some
  good design candidates while keeping an eye on the current iteration.  In
  other words, how to coach a team how to tell the difference between a
  shortcut and a valid minimum viable product that matches with our agreed upon
  design values.
* Methodologies that can enable an agile team to analyze and reason about
  technical debt in a way that can be communicated to different stakeholders.

## What has worked

The most success I have had is when we were able to match a problem with a set
of architecture patterns and found a framework that faithfully implements those
patterns. This provides everyone with the (human) language to have productive
design discussions with each other and stakeholders as well as a corresponding
mechanical language to bring the ideas into existence. On the other hand,
frameworks that have Swiss-army like capabilities can sometimes do more harm
than good because there aren't enough constraints to drive a productive
discussion or present an implementer with a set of viable alternatives.

In terms of organizational structure, splitting developers from a single agile
team into "sub-teams" is promising.  This allows the architect to
divide-and-conquer by giving focused coaching and guidance while empowering a
smaller number of people with finding principled approaches. Teams above a
certain size suffer from a kind of "tragedy of the commons" in which
individuals don't take responsibility for something that they think someone
else could be handling. 

## Summary statement

This workshop should have as a goal identifying a concrete set of practices for
improving software design skills. Currently, this process involves more art
than science and it seems like we should be able to do better.

