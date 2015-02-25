---
title: Starting a New Project
layout: post
---

I always get a warm, fuzzy feeling when I'm starting a new project. You have a clean, simple code base and you promise yourself *this* time you are going to keep it that way. I love setting everything up, installing dependancies, creating a directory structure and making that initial commit.

When I was first setting out that feeling evaporated almost immediately. Straight away I was googling solutions to problems, wondering why something that I thought should be so simple could prove to be quite so difficult. My code was quickly filled with stuff that was there *just so it worked*. Magic numbers everywhere, very specific and limited CSS rules and bloated markup. It wasn't how I wanted to write my code but I didn't know enough to do anything else. When I found a solution I had to take it, and I didn't fully understand a lot of what I was doing.

I like to think things are a bit different now. There's still a huge amount for me to learn, and I'm slowly working through it, but I'm starting to write more and more code that I'm *proud* of. More often I find I can get a simple solution to a problem, using a couple of lines of CSS to do something that before might have taken 15 or doing something that just seems more robust. Layouts that won't fall down if I want to make subtle changes, or a client adds a more text than I anticipated.

A big part of this is preventing specificity problems. Using classes to style instead of CSS selector dependent on markup layout, which I can't overwrite without an !important, or one-upping the previous selector. Another, related part, is making the CSS more modular, more scalable. A huge inspiration in this has been [Harry Roberts](http://csswizzardry.com/) who's written and spoken extensively on how to keep CSS sane and manageable on large projects. I'm not working on projects of the scale he is used to but the principles also transfer beautifully to small projects, even if there's just one author.

Another big influence has been [Nicole Sullivan](http://www.stubbornella.org), of OOCSS fame. Object oriented CSS is about seperating structure from skin and making your CSS rules far more reusable for doing so. You end up with different classes which you can interchange to create new things, without always adding new rules. It took me longer to get my head around this, I saw having a lot of classes in my markup as untidy, but OOCSS is so powerful that once I convinced my self to try it, no obligation, I was soon hooked.

So back to where I started, that warm fuzzy feeling from a new project. I still love, but I'm also starting to love the codebases I work with day in and day out. Instead of just looking forward to starting an new project so I can try and do things better, I enjoy working with what I've got, improving it and building off it.