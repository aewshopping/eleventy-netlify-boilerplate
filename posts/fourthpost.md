---
title: Eleventy on glitch - overcoming initial hurdles
date: 2021-01-03T00:00:00.000Z
author: Anthony
summary: When getting started with eleventy on glitch.com there were a few
  initial 'newbie' hurdles to overcome such as understanding why nothing is
  happening when I changed stuff!
tags:
  - eleventy
---
The trouble is that I was expecting some kind of error message and nothing was visible.

So I kept changing things, introducing more syntax errors without fixing the first ones and getting into a big mess.

Needed to look at log files and fix errors one by one.

### Browser sync

Sometimes the browsersync can trip you up as it updates the browser when you are halfway through typing a formula, thinks the formula is wrong, then the error stops the automatic refresh even when the formula has been fully typed out and is correct.

Needed to either refresh glitch page or use terminal to "force" a build (which I thought I wouldn't have to deal with and nervously but successfully used the commands in the eleventy docs)