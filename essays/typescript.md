---
layout: essay
type: essay
title: "From Frustration to Confidence with TypeScript"
# All dates must be YYYY-MM-DD format!
date: 2025-01-23
published: true
labels:
  - Software Engineering
  - Learning
  - TypeScript
---

<img width="200px" class="rounded float-start pe-4" src="../img/typescript/coding-frustration.jpg">

## Introduction to TypeScript: A False Assumption

When I was first introduced to TypeScript, I hadn’t touched web development in a few years, so I was accustomed to the former industry-standard, Javascript. I thought TypeScript was just an optimized version of JavaScript with a name somehow duller than JavaScript itself. I was very wrong about that assumption. When I actually started using TypeScript, I realized that it was way more than that; it was something to get frustrated at.

## My Frustrating Encounter with TypeScript

As I started writing TypeScript, there seemed to be nothing amiss; I coded like how I remembered. There were even some instances in which I searched for JavaScript solutions when I had to debug. When I was with my page, in the development environment, everything looked good and functions worked properly. I was ready to deploy it. I ran ‘npm run build’, waited around 30 seconds, and then… it returned “build failed.” The error was from ESLint and said:
```
“error: Unexpected any. Specify a different type. (@typescript-eslint/no-explicit-any)”
```
It pointed to a line in which I initialized a variable with an ‘Any’ type. It’s a simple fix looking back at it now, but at the time, I was sleep deprived at midnight and I just wanted to get the task done. So I simply “fixed” the build error by adding this to the top of the file:
```
/* eslint-disable @typescript-eslint/no-explicit-any */
```
“If it works, it works, right?” I thought foolishly. But I later learned that this rule is actually one of the main goals of TypeScript: type-checking. 

## Understanding the Type-checking

Type-checking verifies that there are expected types all across your code. It’s important because it ensures that the operations you’re performing on your values are compatible with each other. For example, if you give an ‘Any’ type to the variable num, which is used in an arithmetic operation, everything will go smoothly if a number is actually assigned to num. But if a string is assigned to num, you’ll run into type issues. The point of no-explicit-any is to prevent num from being assigned anything other than a number. Although I understand why this is necessary now, I can’t help but think fondly of the days when I didn’t need to worry about any of this and just code freely without much restriction.

## Practice Makes Perfect

I am still not fully accustomed to TypeScript, but currently, I am taking ICS 314 at UH Manoa where every week, we have timed TypeScript problems called WODs (Workout of the Day). Having done a few already, they have helped me to get used to specifying types for every piece of data I use. Although the WODs haven’t been too complicated yet, just being able to type TypeScript code makes me more confident and comfortable in the language, which is extremely helpful knowing my past frustrations with it.

AI (ChatGPT) assisted in writing this essay by making the titles and headers.
