---
title: 'Starting Again'
description: 'In which we have another attempt at 100 days of offloading'
author:  'Dunstan Vavasour'
date: '2022-04-22T18:09:28+01:00'
dayof100: 01
tags:
  - admin
draft: False
---

# Writing Again

My previous attempt at *#100daystooffload* kinda hit the buffers around day 23. I got bogged down, life moved on, and I'd made writing a little high maintenance using [write.as](https://write.as).

Don't get me wrong, I like `write.as`, and I think it's a much better platform for blogging than monsters like Wordpress, but I've moved into another platform that I prefer: Hugo.

Nowadays [Markdown](https://en.wikipedia.org/wiki/Markdown) is the *lingua franca* of technical writing: it's pure ASCII source code ready for rendering in whatever way. For me, here and now, on this blog the approach is as follows:

- I write the content in Markdown using VSCode (Yes, I've defected from Emacs)
- I commit my new article to git and push to gitlab
- A gitlab pipeline runs Hugo and creates a rendered page
- The rendered pages are published using gitlab pages

My thinking is this: The mechanism of post writing is incredibly low friction: I have a Hugo archetype that pre-populates the front matter, so I just need to update a few variables and I'm ready to go.

There are some developments to add over the next little while:

- Render this content from my own domain rather than gitlab pages
- Put in a custom footer with *#100daystooffload* boiler plate text
- Work out and improve my taxonomies

Wish me luck!
