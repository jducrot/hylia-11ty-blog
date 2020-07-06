---
layout: layouts/post.njk
title: Let's Do Node
date: 2017-06-22T13:00:00.000Z
tags:
  - node learning
---
## What?

> Node.js is an open-source, cross-platform JavaScript run-time environment for executing JavaScript code server-side. Node.js enables JavaScript to be used for server-side scripting and runs scripts server-side to produce dynamic web page content before the page is sent to the user's web browser.

## Why?

It's a different use of JS and it's used to solve problems I don't think about solving with JS. Clearly, that indicates a gap in my understanding of how it works and how it can be used. Time to fill in that gap.

## How?

Using a few early morning hours each day from Tuesday, June 20th to Sunday, June 25th, 2017 using:

* [Introduction to Node and Express](https://medium.com/javascript-scene/introduction-to-node-express-90c431f9e6fd) by Eric Elliott
* [Introduction to Node: The Fundamentals](https://egghead.io/courses/introduction-to-node-the-fundamentals) on Egghead.io

## Takeaways

1. Node's event-driven, single-threaded, non-blocking I/O model is unlike most other server-side technologies
2. Node's I/O model makes it fast but since it's single-threaded it also means all users share the same memory space. Scoping variables properly is very important.
3. Basics of these frameworks: [Express](https://expressjs.com/), [Supertest](https://github.com/visionmedia/supertest), [Tape](https://github.com/substack/tape)
4. Basics of [PM2](https://pm2.keymetrics.io/) and [REPL](https://nodejs.org/api/repl.html)
1. Global scope and what it contains
1. The Buffer and its main methods

## Worthy Resources Next Time
- [Node School](https://nodeschool.io/)
- [Learn Node](https://learnnode.com/) by Wes Bos
- [The Definitive Node.js Resources](https://x-team.com/nodejs-resources/) by X-Team
