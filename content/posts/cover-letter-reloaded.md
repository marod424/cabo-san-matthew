+++
author = "Matthew Rodriguez"
categories = ["Letter"]
date = "2022-06-28"
description = "A past glance of a path toward future work"
featured = "workstation.jpg"
featuredalt = "My workstation"
featuredpath = "img/2022/06"
linktitle = "2022/06/workstation.jpg"
title = "Cover Letter Reloaded"
tags = ["web development", "job search", "self reference"]
type = "post"

+++

If a résumé is the table of contents, and a CV the abridged version, then this *is* the content...

***

## Origin

I'm a product of my parents, as most of us are. They met in Silicon Valley -- my mother studying for her Master's Degree, my father working as a Computer Engineer. So I come from a technical family. By the time I entered college, my father was working as a patent attorney (often for technical IP) and my mother was teaching highschool AP Computer Science and Web Development. I have an older sister and a younger brother; as a family we love to play games, work on puzzles, and [submerge in mystery](/posts/o-father).

#### Core Principles

1. [**Value education**](/projects/knowledgine): I love to learn, think, explore, and work through problems; I don't sleep as well or attend to my other responsiblities if I am actively stumped -- *working on my equanimity!*

2. [**Faith based**](/posts/ocean): purpose driven, optimistic, and hopeful; introducing practicality into idealism can sometimes frustrate me -- *working on my balance!*

3. [**Relationship focused**](/posts/twins): I believe in collaboration, mentor/mentee relationships, and meaningful conversations; as a peacemaker, I often give into or turn away from arguments -- *working on my conflict resolution!*

### The Early Days

As an undergrad I studied Electrical Engineering and Physics at the University of Delaware.  
I then attended the University of Michigan for a PhD program in Applied Physics.  
But after receiving my Master's degree I left for a myriad of reasons, of which the most impactful two are as follows:
  1. Discovery and the subsequent [studying/exploring/practicing of Hinduism](/posts/my-story)
  2. Frustration with Academia, particularly the strong value on research over coursework coupled with the financial sources and motivations of such research (e.g. military, big pharma)

### Post Graduation

What followed was a solo-trip to India for some soul searching, and I openly bare that I was much (if not more) my old self than (as I was trying to be) someone new.  
Upon return I tutored middle school, high school, and undergraduate students at different times and in different (most gen ed) subjects. *The Great Gatsby* actually made sense to me; it had so much more life and meaning in this flipped perspective as an educator.  
Finally, I worked on coding my first video game/simulation: *Color Game*.

#### Color Game

Perhaps it deserves its own post, but as of yet here are the highlights:  
It was my first effort at self driven coding, beyond work in my highschool Java course and university C++ and Matlab projects.  
After some research I chose Python (for it's gentle learning curve) and PyGame as the game library.  
I learned about and implemented a Model View Controller (MVC) architecture for my game:
  - **M**odel - user entity to control an initially uncolored "soul"; randomly generating colored entities as consumable "soul shards"
  - **V**iew - game board/canvas with 2D pixel graphics
  - **C**ontroller - game loop, interactions, and keyboard controls

### [Dooble](/projects/dooble/)

Landed my first official web application job in NYC.  
Dooble was trying to be a double dating/meetup social application.  
I was a javascript developer, across the MEAN stack (**M**ongo, **E**xpress, **A**ngular, **N**ode)
- *Foot in the door; drinking from a firehose*

***

## A tale of two careers: Formal & Informal

Dooble failed and I lost my job, so I found a junior web dev job in New Jersey and moved.

### Billtrust

I was a small fish, drenched from a firehose, and now swimming in a bigger pond.  
**Billtrust**, a billing and payments business-to-business (B2B) Software-as-a-Service (SaaS) company, was a W/LAMP shop (**W**indows/**L**inux, **A**pache, **M**ySQL, **P**HP) and hired me as the *Javascript guy*.  
As the *Javascript guy*, the goal was to migrate from jQuery to Single Page Applications (SPAs) via AngularJS.  
The highlight was a full reskin of an existing application from jQuery to Angular components over the course of approximately 2-3 months:  
  - Worked closely with a part-time contract UI/UX designer
  - Used *Material Design* as the basis
  - Built an internal component library
  - Refactored old views with new components
  - Implemented new components in all new existing views

Ultimately, I learned full stack, agile development; I worked with product managers, DBAs, QA, DevOps, and of course other developers.  

#### Startup Sabbatical

Well, time passed, seasons changed, and Billtrust was migrating from a monolith to microservices; management was a revolving door and scale was painful.  
Between boredom and frustration, I was wanting for the startup world again!  
Billtrust fully supported me (they were always great at relationships -- I made a ton of friends and had a few great mentors along the way).  
- So I co-founded an [Ed Tech Startup called Knowledgine](/projects/knowledgine)
- And I needed some money, so I started [free-lancing for a company called Anatha](/projects/anatha)

### [Knowledgine](/projects/knowledgine)

The mission is to *democratize education by democratizing educational leadership*.  
The problem is that professor lectures are mostly university siloed educational resources, trapped from the erudite minds of the life-long learners and eager youth alike.  
The tech is a MEAN stack SPA, with a user portal for content consumption (watch, listen, tag, share, like, etc.) and a professor portal for content creation (lecture recording).
- Cloud infrastructure with AWS & Atlas
- Python scripting for professor cold emails to grow the network
- Python scripting for Machine Learning & Natural Language Processing (ML/NLP) of audio transcripts and word/phrase classification for topic relevance
- Node scripting for lambdas (run python scripts by spawning node processes)

### [Anatha Freelance](/projects/anatha)

This was 2018, and crypto was the new hotness.  
I landed a 3 month contract job to work on a blockchain/web3 application: smart crypto wallet  
- Desktop application via Electron (JS)
- ReactJS, third party APIs to communicate with crypto chains
- D3 for data visualizations, amongst those where I solved a self-coined *Boundary Problem*
  - Pie chart visualization with labels for each slice of the pie
  - Crowded UI towards the "Boundary" for the smaller percentages
  - Easy solution is to label with "other", but the percentanges were often crowded towards the lower end due to the nature of crypto coins portfolios (small holdings of alt-coins)
  - I set up a system of equations and solved for the boundary conditions to dynamically determine *when* and *how* to show the labels in different aesthetic ways

### Return to Billtrust

Time had passed since my last foray with Billtrust, when a good friend and former colleague asked me to return as a contractor.  
Billtrust was now a microservice shop with a C# backend, an Angular frontend, and a platform team for building out Identity and Access Management (IdAM) and an internal component library (UI/UX).  
I was tasked with migrating an existing application from *Material Design* based components to the new internal components.  
And so, a different season, a new day; a different app, a new reskin:
  - The first thing I did was try to lose my job by recommending against the work (not worth the time cost and added insignificant product differentiation, IMO)
  - The business desire to merge all applications under the framework prevailed, I kept my contract job
  - **Findings**: worse performance than existing app
  - **Result**: fixed performance issue for entire platform component library (thanks to AoT vs JiT compilation)

I was subsequently hired full time to work as full stack developer on greenfield apps and services.

#### Personal Sabbatical

Well, time passed (again), seasons continued to change, and Billtrust was hiring a multitude of off-shore resources; management was an ever expanding revolving door and scale was even more painful.  
Between boredom and frustration, I was wanting to work my passions into a career:  
- So I created this blog
- I began streaming variety video games and tried my hand at content creation
- And then I taught at *The Frisch School*

### Cabosante

You are Here!
- Uses Static Site Generation (SSG) via Hugo and a TOML templating engine
- Has cloud server Github integration for automatic deployments
- Integrated blog content with daily streaming during my [*Stadia Advent*](/posts/stadia-advent)
- Created and streamed a World of Warcraft metagame, called [*Legacy*](/posts/wow-legacy)

### Frisch

An unexpected experience of a lifetime!
- Private Jewish Modern Orthodox high school in North Jersey
- Teaching high school AP Computer Science and Honors/Accelerated Physics
- Fully remote (teaching over Zoom)
- Preparing CS students for AP exam (Java)
 
### Anatha

It was time to work again, professionally.  
*Anatha* had since raised money from the desktop wallet I helped develop while [free-lancing](/projects/anatha).  
The company even built its own blockchain and native cryptocurrency asset!  
They wanted a crypto NFT platform and hired me as a technical lead for the onset:  
  - I worked with 2 other devs and 1 automation engineer on a NFT gallery application coupled with a blockchain indexer  
  - We chose Turborepo, NextJS (react), Vercel, and Node for our MVP stack
  - We completed the MVP in May...

And then, the market crashed; the company lost major investments and let go of all development teams.  

**What's next?**  
- Something professional - $$$ is helpful  
- Something personal - food for the soul  

**Why not both?**