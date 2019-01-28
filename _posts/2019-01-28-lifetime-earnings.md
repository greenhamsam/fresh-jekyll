---
title: What might you earn over the rest of your lifetime?
layout: post
categories: freedom
tags: [freedom, earning, making money]
published: true

images:
    - url: /images/lifetime-earnings.png
      alt: Lifetime earnings table
      title: Lifetime earnings table
---

Visualise all the money you're still going to earn over the rest of your life. Close your eyes and picture it for a moment, a big pile of cash, like something Scrooge McDuck might go swimming in.

<!--more-->

Can you see it?

Imagine picking up one or two of those pieces of paper. Each bit of cash is a piece of possibility. You could do anything with it.

Have you ever stopped to think about how big that pile might actually be?

Here's an estimate for you, based on your age and your monthly income:

{% assign image = page.images[0] %}
{% include image.html image=image %}

Holy shitballs, that's a big number, right? How much of that money are you going to spend on the stuff that really matters to you?

#### How'd I work out that number?

Basically, I use this formula:
Lifetime earnings = (current salary x 12) x ((((1.06) ^ (65 - current age)) - 1) / 0.06)
