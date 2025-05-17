---
layout: project
type: project
image: img/gymbuddy/rec-center.png
title: "Gym-Meet"
date: 2025
published: true
labels:
  - Next.js
  - PostgreSQL
summary: "A platform that helps UH Manoa gymgoers find new people to go to the gym with"
---

<img class="img-fluid" src="../img/gymbuddy/explorepage.png">

## The Problem
For many university students, their first introduction to the gym is the Rec Center. They want to be more active but are too intimidated to go to the gym alone. They are discouraged by their lack of experience and knowledge of the machines, as well as the fear making mistakes and injuring themselves. To overcome this, they opt to invite their friends to come along with them. But oftentimes their schedules don’t match up, which deters them from going.

## Our Solution
Our gym-meet app allows students to connect with others according to their workout needs and go to the gym together. Students will create their own customizable profile with their weekly gym times, frequent exercises, experience level, and more! They will then be able to match and meet with other people who have similar schedules, skill level, and workout preferences, and feel more comfortable going to the gym with a buddy! We hope this will also foster a greater sense of campus community by bringing together students who wouldn’t normally interact and get to know people across different majors.

## My Contribution
One of my main tasks was to create the Explore page (imaged above), which displays all of the registered users on the site. I had a lot of fun with designing the cards because there was a lot of info about each user that I could pick and choose to include in the cards. Along with the design, I also connected the explore page to the backend, so it successfully fetched all users from our PostgreSQL database. A small side feature that is slightly noticeable in the picture, is an Add/Remove Friends feature on the top right of each profile card. Configuring this in the backend was interesting because I had to create a new table, and link each user with their friends and vice-versa, then make that implementation show in the frontend. Overall, this project gave me a boost in full stack development and working in a team environment.

[Gym-Meet Infopage](https://gym-meet.github.io/)

[Gym-Meet Deployment](https://gym-buddy-five.vercel.app/)

[Gym-Meet Source Code](https://github.com/gym-meet/gym-buddy)
