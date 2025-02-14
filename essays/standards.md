---
layout: essay
type: essay
title: "Digging Deep Into The Errors"
# All dates must be YYYY-MM-DD format!
date: 2025-02-13
published: true
labels:
  - Software Engineering
  - Typescript
  - Learning
  - Collaboration
---

<img width="100px" class="rounded float-start pe-4" src="../img/standards/eslint.png">

When people think of coding standards, they often imagine stylistic rules like indent lengths, where to place curly braces, and how to format comment blocks. However, coding standards mean far more than just aesthetics; they are important software engineering practices that improve code quality, readability, and maintainability. On top of that, they also facilitate learning and understanding of programming languages.

## My Experience with typescript-eslint

Recently in my ICS 314 Software Engineering class, I was introduced to ESLint, a powerful tool for enforcing coding standards and preventing potential compilation issues in Typescript. Initially, my experience with typescript-eslint was frustrating. My IDE, VSCode, with ESLint plugins, would underline every little ESLint error in red. This constant feedback became overwhelming at times, especially when encountering errors that cannot be resolved immediately, such as the, "[variable/function] is declared but never used," warning while I’m in the middle of writing a function.

While these initial frustrations made ESLint feel like a hindrance, over time, I began to notice its benefits. The strict enforcement of coding standards forced me to understand Typescript deeper. When I was faced with errors I could not resolve, I often turned to GitHub Copilot for assistance. However, Copilot did not always provide the right solution, and sometimes its fixes introduced new problems. This led me to investigate the root causes of the errors myself, in turn giving me a better grasp of Typescript. This is one of the unexpected benefits of adhering to coding standards: they act as an educational tool. By consistently enforcing best practices, tools like ESLint encourage developers to write better code and adopt good habits early. They provide real-time feedback, highlighting potential pitfalls and guiding developers toward more efficient solutions. Through ESLint, I learned about Typescript-specific rules, proper variable scoping, and best practices that might have taken longer to grasp.


## The Broader Importance

Beyond personal learning, coding standards are also essential for collaborative development. Most software is not going to be seen by just one developer; it is continuously revised, expanded, and maintained by multiple developers. A shared coding standard ensures that all contributors can easily understand and work with the codebase, reducing onboarding time, preventing inconsistencies, and avoiding headaches. In one of the projects I’ve worked on, all of us had been new to web development at the time so we had not enforced a coding standard. As a result, debugging and integrating my code with my groupmates' was challenging due to our differing coding styles and approaches; the same likely could’ve been said about my code as well. A unified coding standard ensures that code remains readable, maintainable, and scalable.

Initially, coding standards and ESLint felt like a bother. However, my experience has shown me that they serve a much greater purpose than simple style enforcement. They enforce good coding habits, help developers understand a programming language, and ensure that code is readable and maintainable in team-based environments. While they may be frustrating at first, I believe their long-term benefits outweigh the initial learning curve.

AI (ChatGPT) assisted in writing this essay by making the titles & headers, and improving transitions & flow.
