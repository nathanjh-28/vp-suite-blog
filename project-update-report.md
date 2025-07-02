---
layout: page
title: Project Update Report
permalink: /project-update-report/
---
*by Nathan J Harris* <br>
*July 1, 2025* <br>
*CSPB 3112 Professional Development* <br>

## Brief Summary of Project and Proposal
**Project**: A full stack application that features a project management suite of tools based on my client's video production company's business logic and workflow.

In my [proposal]({{ site.baseurl }}/proposal), I outlined three overlapping modules:

**Project Planning Documentation**: To scope, design, and roadmap my entire full stack project and it's features clearly.

**Backend Learning & Practice**: Learn C# and .NET Core, including database integration and round out a deeper skillset for the backend.

**One-Feature API Implementation**: Build a core feature of my project in addition to user authentication and authorization while having all the systems in place to continue working through the remaining features of the project after the professional development course ended.

**Optional Module, React Frontend**: A stretch goal if time allowed.  If not, mock ups from the planning docs would serve presentation needs.

## Progress
Each week I have taken a topic and explored it through tutorials, videos, and then used the information to build a miniproject inspired by my main project.  Each one of these topics and applications will be a part of my final project.

This is what I have completed so far:
- Learned C# Fundamentals building an Object Oriented Console Application
- Learned and built a basic web api with in memory data
- Learned Entity Framework Core with SQLite and built a web api with persistant data
- Dived deep in to test driven development and learned how use the xUnit testing framework, how to write unit tests, integration tests, test api routes and put a SQLite db in to memory for testing.
- Project Planning Documents are about 60% complete mostly from before the course.  Recently I planned out all the [API endpoints]({{ site.baseurl }}/api-endpoints) that mapped to the database.
- Stayed on weekly schedule (with a toddler and baby at home it feels like a major accomplishment!)

## Altering Course
It is obvious from my proposal that I bit off more than I can chew. The cost has been my mini projects, which typically I run out of time and come up short from my initial plans. I haven’t had as much time for my project planning documents as I would have liked. Moving forward instead of working on mini projects to apply my learning I will work on my one-feature project directly, possibly in a separate branch to isolate code for learning. 

I decided that I need to step away from developing my skills and spend one week to exclusively build out the api as well as focus on my project planning documentation.

Finally, I have taken this moment, and this report to consider what I wanted my project to look like at the end of semester. I decided that having only an API that output JSON alongside wireframe mock ups would feel unfinished to me and not particularly presentable. To remedy these feelings I decided to devote one week in my schedule to refresh my React skills and build a modest front end. I realized my one-feature app won’t require much, perhaps just a handful of React components with a single call to the API per webpage. Even if I decide to make a vanilla web user interface, with what I already know, I should be able to get it done in one week.  I have had to shuffle around some of the learning objectives from my initial schedule to accommodate these changes.  I feel much better about this schedule. It is interesting that the initial weekly schedule, which was made by ChatGPT, felt foreign and I was skeptical that it covered all my bases.  Looking at my updated weekly schedule, with much more insight, I am more confident.

## Changes to Project and Proposal

I have added building out a minimal front end web interface to accompany my simple but highly professional .NET Core web API.

If I don't get to some of the topics near the end of my weekly schedule I am okay with that since I will have a presentable project.

## Updated Weekly Schedule

#### *Summary of changes:*
- folded input validation and error handling in to the week on testing
- merged API Design and Documentation in to the Clean Architecture Week and the Final Week
- added one week to focus on building API and one week for minimal front end user interface.

#### Weeks Completed:
Week 1: Explore learning resources and project implementation ideas <br>
Week 2: Firm up scope and project proposal <br>
Week 3: C# Fundamentals <br>
Week 4: ASP.NET Core Basics <br>
Week 5: CRUD with Entity Framework Core <br>
Week 6: Unit and Integration Testing

#### Current Week: 
Week 7: User Authentication and Authorization

#### Remaining Weeks:
Week 8: Implement One-Feature Web API with User Auth<br>
Week 9: Minimal Front End with React <br>
Week 10: Containerize with Docker and Deployment <br>
Week 11: Logging and Monitoring <br>
Week 12: Clean Architecture, CI/CD Pipelines <br>
Week 13: Final Polish, Documentation, Presentation, Final Report
