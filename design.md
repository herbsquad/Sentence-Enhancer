# Design document for the Sentence Enhancer Web Application
Authors: Derek Herbert, Tyler Herbert  
Last Modified: May 16, 2019


### Overview
This document outlines the design for a "sentence enhancer" web application. The proposed application will listen for configured keywords in a microphone audio stream; when a configured keyword is detected, a configured sound is played through users microphone.

E.g. "Get wrecked" is heard, ham horn noise plays.

### Context
This project's primary purpose is to allow the authors (Tyler and Derek) to demonstrate their ability to manage and execute the design, creation, testing and deployment of a web application using modern web development practices and technologies. 

The secondary purpose is to create a fun and useful tool for gamers and streamers that allows them to play whimsical noises without having to change windows/applications and play them actively (like you would with a soundboard).

### Goals and Non-Goals
The Goals section should:

describe the user-driven impact of your project — where your user might be another engineering team or even another technical system
specify how to measure success using metrics — bonus points if you can link to a dashboard that tracks those metrics
Non-Goals are equally important to describe which problems you won’t be fixing so everyone is on the same page.

### Milestones
A list of measurable checkpoints, so your PM and your manager’s manager can skim it and know roughly when different parts of the project will be done. I encourage you to break the project down into major user-facing milestones if the project is more than 1 month long.

Use calendar dates so you take into account unrelated delays, vacations, meetings, and so on. It should look something like this:

Start Date: June 7, 2018
Milestone 1 — New system MVP running in dark-mode: June 28, 2018
Milestone 2 - Retire old system: July 4th, 2018
End Date: Add feature X, Y, Z to new system: July 14th, 2018

Add an [Update] subsection here if the ETA of some of these milestone changes, so the stakeholders can easily see the most up-to-date estimates.

### Proposed Solution
The proposed solution has 7 major pieces:
  1. An interface to create/manage user accounts.
  2. An interface to configure keywords/audio to listen for.
  3. An interface to upload sound bytes to play when keywords are detected.
  4. A method for sending a live audio stream from user's mic (from browser) to our server.
  5. A method for recognizing keywords in live audio stream
  6. A method for outputting sound byte through user's mic (from browser)
  7. Payment processing API integration with Stripe

### Testability, Monitoring and Alerting
I like including this section, because people often treat this as an afterthought or skip it all together, and it almost always comes back to bite them later when things break and they have no idea how or why.

### Cross-Team Impact
How will this increase on call and dev-ops burden? 
How much money will it cost? 
Does it cause any latency regression to the system? 
Does it expose any security vulnerabilities? 
What are some negative consequences and side effects? 
How might the support team communicate this to the customers?

### Open Questions
Any open issues that you aren’t sure about, contentious decisions that you’d like readers to weigh in on, suggested future work, and so on. A tongue-in-cheek name for this section is the “known unknowns”.

### Detailed Scoping and Timeline
This section is mostly going to be read only by the engineers working on this project, their tech leads, and their managers. Hence this section is at the end of the doc.

Essentially, this is the breakdown of how and when you plan on executing each part of the project. There’s a lot that goes into scoping accurately, so you can read this post to learn more about scoping.

I tend to also treat this section of the design doc as an ongoing project task tracker, so I update this whenever my scoping estimate changes. But that’s more of a personal preference.
