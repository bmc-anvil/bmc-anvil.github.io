---
title: "What is BMC Anvil"
permalink: /what_is_beginning/
excerpt: "How it all started"
header:
  overlay_image: /assets/images/hero-kanban-light.jpeg
  caption: "ScreenCapture: bmc anvil kanban"
layout: single
toc: true
toc_sticky: true
sidebar:
  title: "What is BMC Anvil"
  nav: sidebar-about_anvil
---

# Beginnings

**Anvil** started like a skills showcase to help with interviews as a developer on my main notes
site: [Bare_Metal_Code](https://www.baremetalcode.com/).<br>
You can find the [original notes for anvil](https://www.baremetalcode.com/bmc_showcase/) and
the [showcase's github repo](https://github.com/JohnnyXavier/bare-metal-flow) following the previous links.

The original idea was to practice and train a little on typical concepts by coding something more than isolated snippets.

There are many resources were we can read snippets for hibernate, inheritance or polymorphism. There are already enough mini demos out there
and my question when learning a few concepts was...

***"Ok..., and how do I put all of this to work in real life?"***

Not just how to code a `MappedSuperclass` with hibernate, the snippets are clear enough. But, when do I need one? do I ever? Where a design
patter is useful? etc...

Eventually I added a proper UI, wired it with the back end and modified the UI to become a semi finished product. That way the showcase and
notes will make a bit more sense.

So that's how it started.

# Moving on

## part I

So... the showcase ended up growing and then well... I showcased it to a few friends...

I was encouraged to continue working on it and publish it as a real app. There was a caveat thou...

As all this started as a skills showcase, I pushed a few concepts to the limit to show different approaches for a given problem, or to show
how much one can get out of some OOP concepts...

For example, there several approaches to data / db management. Pure ORM, ORM managed projections (panache), named queries, queries on
entities, direct transaction on services, etc...

That zoo of approaches makes sense if you want to showcase your knowledge, but I've never seen all that used in a single project at the same
time. It just won't make much (any...) sense... (at all...)

Another point is that the showcase app itself was very ambitious on a few topics and I completely dropped others on purpose, making it a non
viable production ready app. The showcase app has close to 50 tables, similar amount of endpoints, local caching, but all of it without an
approach built for code scale.

It is a very fine interview showcase app, but will fall in the category of *"another one bites the dust" poorly architected to stand the
time app*.

It is just fine for what it is, but not for what it could be...

I did not had the time to do a showcase of architecture, on top of the daily coding concept knowledge, and after landing a few jobs I had to
pause some articles (I'll get to them soon enough...)

## part II

So then, I found some quiet and thought about converting this into something usable beyond the showcase scope but keeping the same spirit,

I got a pen and a notebook and starting breaking down the app, adding modules, proper separation of concerns, checking approaches for code
sustainability, etc.

## part III

The result is this app, again a showcase app, were I will try to pour some lessons from the previous one, plus an architecture showcase on
several topics:

- dev:
    - broad architecture:
        - components binding, (http, events, queues, etc)
    - modular architecture
        - module architecture, (ddd, ports/adapters, etc)
    - Deep Learning
    - Security and Auth
- devops:
    - ci/cd
    - pipelines / actions
    - infra as code

and a few more...

This app, while keeping the spirit of a showcase, will not have a zoo of approaches to a same problem as I did before.
I will instead focus of making a showcase of the tech and experiences of building a real app from scratch. There will mistakes, dev guides,
setups, hand made charts pictures, etc.

Hope this will help others as reading books helped me, and why not, pay a beer or two if it turns out to be a marketable idea.