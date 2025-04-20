---
title: "From 100 to 101: The Limits of AI Collaboration and Human Positioning"
date: 2025-03-30T00:23:16+08:00
tags: [AI, Programming, Vibe Coding, Tech Notes, Technology Trends]
categories: ["Tech Reflections"]
draft: false
description: "This article explores the challenges Vibe Coding faces when dealing with complex systems, and how engineers can define their place in an evolving development landscape."
---

## From 100 to 101 – A Small Step for You, a Giant Disaster for the System?

As your project grows larger, there may come a point where your snake suddenly can’t turn? Users report their scores aren’t updating correctly? Or maybe when the snake gets long enough, the screen starts to lag, data fails to save, or weird crashes occur—how exactly is AI supposed to debug this? And how is it supposed to solve it?

This, I believe, is currently one of the biggest challenges. AI performs relatively well on single-target tasks. But when the destination keeps moving, or the problem becomes complex and interconnected, it’s often not that easy. Among the examples above, system lag might be the hardest for AI to solve. When we try to get AI to solve such issues, it often suggests several directions and tries them one by one. If we're lucky, the problem gets solved quickly. If not… it might be the beginning of something worse.

That said, we humans often solve problems in the same way. Sometimes we “intuitively” hit the right spot (lucky guesses?), and sometimes we wander into the unknown and make things worse. So on this point alone, maybe we and AI are on equal footing.

## Solving Problems or Creating New Ones?

But is this really unavoidable? I don’t think so.

The key, as we’ve repeated over and over again, is the **prompt**—especially a **precise** one.

We can break this down into two parts:

### Part 1: The Root Cause

As mentioned earlier, in the journey from 0 to 1, having a clear goal helps AI follow your intent and generate the right code. So to solve a problem, we need to tell AI the exact root cause.

Going back to the Snake game lagging—if we can identify that a particular loop or a function calculating the tail’s coordinates is too slow, or that there’s an endless `for` loop somewhere, I think AI has a good chance of fixing it. But just saying “lag” isn’t precise enough—for either us or AI.

As humans, we might try to reproduce the issue first, then narrow it down using `perf` or logs. AI might go through the same trial-and-error process if only given the vague word “lag.”

### Part 2: Mastery

For an experienced engineer, similar issues might immediately trigger memories of past code or system commands that could help. Can AI reach that level of mastery? I’m not sure—but I think it’s just a matter of time.

As long as we can feed the full project context and code into the AI, and as long as it has enough memory and processing power, I believe AI could understand the structure of the project better than we do. It has huge potential in time and space complexity analysis—especially if it has enough context and complete code. It might one day analyze faster and better than us. While recursion and asynchronous logic still pose challenges, I’m optimistic about future improvements.

## How Software Engineers Should Adapt

So, where do we go from here? Even if AI can technically solve 80% of problems, that doesn’t mean we humans are “useless.” The remaining 20%—the tricky edge cases—often define the user experience and product quality.

First of all, there’s no need to panic. Having the necessary computational resources and memory isn’t free—it costs money and depends on project scale.

Second, there are still gray areas between hardware and software that require human judgment. For example, in Wi-Fi packet processing, some reserved memory can’t be released until the packet is fully sent. Otherwise, transmission could be affected. In static analysis or testing, we often have to tell tools: “This isn’t a bug, and it’s not a memory leak either.” Maybe AI will learn to understand that someday, but for now, we still need to define these boundaries ourselves.

So what can we do? Beyond embracing AI’s efficiency, we should also upgrade our broader skill sets—especially in two areas: **breadth of thinking** and **breadth of knowledge**.

### 1. Breadth of Thinking

In my not-so-long career, I’ve noticed a pattern among great engineers: they treat every problem as something solvable through code. But maybe I’m a bit lazier (?), or maybe I had a mentor who taught me well—I believe not every problem is actually a problem. Looking at things from different perspectives can lead to completely different solutions.

When working with AI, this mindset is even more crucial. From my experience, AI tends to stick closely to the problem you gave it, trying to give “the correct” answer. Sometimes, it gets stuck in an endless loop of options A, B, and C. But honestly, we need to admit—not every problem has a solution. And sometimes, an approximate, “good enough” answer is all we really need.

### 2. Breadth of Knowledge

In the early stages of growth, absorbing a wide range of concepts gives us the foundation to go deeper. You need to have **heard** of new terms, **seen** new ideas and technologies before you can collaborate with AI effectively to explore them.

Why not use this AI-assisted productivity boost to explore more of the world? Try filtering through this overwhelming information age and store useful things in your mind—you never know when you’ll need them.

## In the End: Language Is the Starting Point

One last cliché—but important—point: **soft skills**. And the most important of those? Communication and storytelling.

To put it more bluntly: being able to explain what you’re thinking in your own words.

You might ask, “Why does it matter if people understand me?” But seriously—don’t forget the hottest AI models today are all LLMs: **Large Language Models**. At their core, they’re still about language.

If we can’t describe what we think with clarity, we can’t even take the first step—whether we’re talking to people, or to AI. Learn to communicate, to sketch out the blueprint in your head. That will always be the real beginning.
