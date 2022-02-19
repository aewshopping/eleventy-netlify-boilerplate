---
title: Getting the netlify CMS to work
date: 2022-02-19T22:13:21.270Z
author: Anthony
summary: Getting the netlify CMS to work - problems I found and some solutions
tags:
  - eleventy
---
The first problem in the boilerplate code that I copied over was that it was calling my main branch "master".

In github my main branch was called "main". Updating this in the config file allowed me to access the Netlify CMS and overgame and Gateway error.

Still need to figure out how to load my collections though...