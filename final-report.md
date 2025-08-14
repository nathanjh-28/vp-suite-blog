---
layout: page
title: Final Project Report
permalink: /final-project-report/
---

*by Nathan J Harris* <br>
*August 14, 2025* <br>
*CSPB 3112 Professional Development* <br>

## Introduction
<!-- Include your project vision and goals -->
This project focused on building the foundational layer of a client-centered project management application for video production companies while learning C# and ASP.NET Core web development. The primary goals were to expand my backend development skills through hands-on application of enterprise-level technologies and to create a functional software solution that addresses real business challenges faced by my client's video production company.

The project served dual objectives: advancing my technical expertise in modern web frameworks and delivering tangible value through custom software development for small business operations.

## Background
<!-- What is the project about, and how is this important to you and your professional development? -->

This project originated from collaborative discussions with a client who operates a small but active video production company. Currently, the business relies on a fragmented system of management tools: Trello boards for project status tracking, Google Sheets for financial management, and various ad-hoc solutions for client and collaborator interfaces. The proposed application aims to consolidate these disparate workflows into a unified platform with a centralized database and role-based access control.

The initiative aligns closely with my professional interest in developing software solutions that streamline small business operations by translating core business logic into intuitive, efficient digital tools. This focus represents a strategic career direction toward serving the technology needs of small enterprises through custom software development.

To maximize the professional development value of this project, I deliberately selected .NET Core and React as the primary technology stack—frameworks outside my existing expertise. This choice was intended to expand my backend development capabilities and familiarize myself with enterprise-grade tools commonly used in professional software development environments.

Recognizing the ambitious scope of creating a comprehensive project management suite, I adopted a pragmatic approach by focusing on foundational elements: implementing core authentication and project management features, establishing a robust development pipeline, and creating detailed specifications for future functionality. This strategy ensures a solid foundation for continued development beyond the course timeline while demonstrating mastery of professional development practices.

My existing full-stack development background provided a strong foundation for this undertaking, which enabled me to focus specifically on backend architecture challenges and advanced development methodologies rather than fundamental web development concepts.


## Methods
<!-- What did you use to obtain the knowledge and/or skills? -->

The learning framework for this project was adapted from a Java Spring Boot curriculum template provided by the course instructor, which I modified to address .NET Core and related technologies. This adaptation resulted in a structured weekly schedule covering all targeted learning objectives, with primary resources drawn from Microsoft Learn tutorials and official documentation.

My learning methodology followed a systematic two-stage approach designed to maximize knowledge retention and practical application. The initial stage emphasized comprehensive material absorption through multiple learning modalities: video tutorials, technical documentation, articles, and hands-on coding exercises using sample projects. The second stage focused on knowledge internalization through practical application, where I implemented newly acquired concepts in either standalone mini-projects or dedicated branches within the main project repository.

This dual-stage process proved particularly effective because it created opportunities for meaningful error recovery and problem-solving—critical components of technical skill development. The methodology mirrors established pedagogical principles familiar from traditional coursework, where theoretical learning (readings, lectures, assessments) is reinforced through practical application (assignments, projects).

At the midpoint of the semester, I transitioned from structured technology learning to concentrated project development. This shift allowed me to apply accumulated knowledge while simultaneously developing professional skills in version control, project documentation, and software implementation. During this phase, I successfully established the foundational architecture and core functionality of the application.

Following the intensive development period, I returned to structured learning to address frontend development and DevOps technologies, culminating in the successful deployment of the completed application during the final week. This cyclical approach—alternating between focused learning and practical implementation—provided a comprehensive methodology for both skill acquisition and tangible software development within the course timeline.

## Results

<!-- What did you learn?
How do you know you have learned it?
What were your project assessments, and did you reach those goals? -->

This project successfully delivered a minimal full-stack application utilizing C# and ASP.NET Core—technologies new to my development toolkit—while implementing test-driven development practices and modern DevOps workflows. The completed system includes a React frontend with Material UI component library, containerized deployment infrastructure, and comprehensive project documentation. The API is deployed using Docker containers on Render.com, with the frontend hosted on Vercel.

### Assessment Against Original Measurable Goals
The following analysis evaluates project outcomes against the specific objectives outlined in the initial proposal:

> *"Finalize core project planning materials, including user stories, ERD, API routes, and wireframes"*

I successfully completed the essential project planning documentation, though with a strategic focus on breadth rather than exhaustive detail. The GitHub repository features a comprehensive README that covers key project planning elements while linking to detailed breakdowns of specific components. This approach prioritized actionable documentation over comprehensive theoretical planning.  

> *"Gain working knowledge of C# and ASP.NET Core by applying concepts from official tutorials to build the project’s backend"*

I achieved functional proficiency in .NET Core development through a multi-modal learning approach incorporating tutorials, technical documentation, video content, and hands-on debugging. The working application demonstrates practical mastery of the framework's core concepts and architectural patterns.

> *"Implement user authentication and CRUD operations for one core entity (Projects) using a relational database"*

I successfully implemented both user authentication with a complete User entity and full CRUD operations for the Project entity. The authentication system is fully functional when accessed through API testing tools such as Scalar or Postman. Integration with the React frontend remains incomplete, representing a defined scope limitation rather than a technical failure.

> *"Write tests for key backend logic"*

Testing proved to be one of the most challenging aspects of the project, requiring multiple iterations to achieve stable functionality. The final test suite includes unit tests covering business logic within service layers and integration tests utilizing in-memory SQLite databases for endpoint validation. While not achieving full coverage, the implementation demonstrates competency in test-driven development principles and practices.

> *"Deploy the backend using Docker and CI/CD tools"*

I successfully established a complete DevOps pipeline featuring GitHub Actions for continuous integration/continuous deployment, Docker containerization, and cloud hosting through Render.com. This infrastructure represents production-ready deployment practices.

> *"Document the API and maintain a well-organized GitHub repository with clear version control practices"*

I developed and implemented professional version control workflows including branch management, pull request protocols, and standardized templates. Additionally, I utilized GitHub's project management features—milestones and issues—for the first time, expanding my understanding of collaborative development practices.

> *"Minimal Viable React Front End using Material UI Component Library"*

The frontend application successfully demonstrates the core functionality while maintaining focus on the Project entity. This addition proved valuable for design validation and provided a tangible interface for project demonstration, though it remains intentionally minimal in scope.

### Project Assessments
> Project Planning documentation complete and client reviewed

Essential components completed with strategic focus on implementation-ready specifications rather than exhaustive documentation.

> Backend API Meets functional requirements

Functional requirements successfully met for both user authentication and project management features.

> Tests verify core functionality

Implemented tests verify core functionality, with coverage sufficient to demonstrate testing competency and methodology understanding.

> Successful Deployment and Containerization

Successfully achieved using industry-standard tools and practices.

> Clear, professional project documentation

Comprehensive and well-organized, though with potential for expansion in future iterations.

## Risks and Mitigation Strategy - Review
The project proposal identified four primary risks with corresponding mitigation strategies. The following analysis evaluates the effectiveness of each approach and provides insights for future project planning.

### 1. New Language and Framework
#### Risk Assessment:
> I am using C# and ASP.NET Core for the first time in a production-style project. While I have experience with other languages and frameworks, learning and applying enterprise-grade tools in a short timeframe presents a challenge.

#### Mitigation Strategy:
> I will follow well-structured, goal-oriented tutorials from Microsoft and other trusted sources, and apply new concepts incrementally through the project’s phases.

#### Strategy Effectiveness:
This mitigation approach proved largely successful due to its emphasis on structured, goal-oriented learning. The combination of progress reports and project-specific requirements provided essential scaffolding for intensive skill acquisition within a compressed timeframe. However, a significant challenge emerged in identifying current, relevant learning resources. Considerable time was lost evaluating and selecting appropriate tutorials and documentation.

In retrospect, adopting an established curriculum or proven learning path might have improved efficiency. Nevertheless, given the self-guided nature of this project and the 12-week constraint, resource identification challenges were anticipated and acceptable trade-offs for the flexibility of a customized learning approach in a compressed time frame.

### 2. Limited Project Hours

#### Risk Assessment:
> The course allocates only 3–4 hours per week to the project, which includes blogging and piazza participation. This time constraint requires careful planning and scope management.

#### Mitigation Strategy:
> Mitigation Strategy 2. Dedicated learning time outside course hours:
I am allocating an additional 9 hours per week outside the course to support the depth of learning and implementation required.

#### Strategy Effectiveness:
The expanded time allocation strategy was essential to project success, enabling substantially greater progress than would have been possible within the prescribed 3-4 hours weekly. However, maintaining the planned 9 additional hours proved challenging when competing academic and personal commitments arose. This variability in available time reinforced the importance of flexible project planning and realistic scope management.

### 3. Integration Complexity and Minimum Viable Scope
#### Risk Assessment:
> Coordinating authentication, database integration, testing, deployment, and documentation into a cohesive backend API may be more complex than anticipated within the course schedule.

#### Mitigation Strategy
> I have intentionally limited the project to one or two core features (user authentication and minimal project tracking) to ensure successful delivery within time constraints.

#### Strategy Effectiveness:
This proved to be the most critical mitigation strategy, enabling deep exploration of a new technology stack without the pressure of delivering comprehensive functionality. The deliberate scope limitation facilitated focused skill development and established a solid foundation for future expansion. While resulting in a basic application, this approach prioritized sustainable learning and professional skill acquisition over feature completeness—a strategic decision.

### 4. Front End Development Scope Management
#### Risk Assessment:
> Building a frontend in React is not required for this project but is a potential stretch goal. If not carefully managed, this could compete for time with more critical backend objectives.

#### Mitigation Strategy:
> The frontend portion is clearly scoped as a bonus objective. If time allows, I will begin development using React and Material UI. Otherwise, wireframes and API documentation will clearly demonstrate how the backend is intended to be used.

#### Strategy Effectiveness:
I deviated from this mitigation strategy at the semester's midpoint, choosing to develop a minimal React frontend despite the associated time costs. This decision merits careful evaluation. While the frontend component enhanced project demonstration capabilities and provided valuable design validation, it represented a departure from the planned scope management approach.

The trade-off yielded a more presentable final product but diverted resources from potential backend feature refinement or additional DevOps exploration. This experience highlights the ongoing tension between project scope discipline and the appeal of tangible, demonstrable outcomes.

## Reflection

<!-- Did you meet your goals?
If yes, what did you do that allowed you to reach them?
If not, what did you do that did not allow you to reach those goals, and how would you change your approach to succeed in the future?
How do you feel about the project results? -->

While my ambitious project scope prevented me from achieving 100% of my stated goals, I can confidently assess that I reached approximately 80% completion, a benchmark that proved remarkably consistent throughout the semester. This pattern of setting ambitious weekly objectives, consistently falling short of complete achievement, and then advancing to the next topic became a defining characteristic of my learning approach.

This methodology prioritized breadth of professional skills over depth in specific technical areas or comprehensive project implementation. The experience was characterized by alternating periods of frustration and exhilaration. As I reflected on our course forum in a post, working within constraints that exceeded my time allocation actually enhanced my motivation rather than diminishing it:  

> I’ve discovered that setting ambitious weekly goals, ones I often don’t fully achieve, actually keeps me more motivated than setting “realistic” targets I know I can hit. While this might sound counterproductive, these stretch goals inspire me to squeeze project work into small moments: researching during 5 minute breaks, dictating ideas while driving, or taking notes while waiting in line. When I inevitably fall short, I’ve learned to reframe the experience from “coming up short” to “look how much I accomplished.” This shift in perspective has been crucial, instead of feeling crushed by missing targets, I feel genuinely proud of the progress I’ve made. The key insight for me is that I’m in charge of these goals and can modify them anytime if they truly become unworkable. I call this “ambitious pragmatism,” using big dreams as motivational fuel while staying flexible about outcomes. This approach works for my personality and circumstances, though I recognize others might find more sustainable motivation in other ways.  I feel that this course and this project has really helped me discover this balance for myself. 

### Alternative Approaches and Trade Offs
In retrospect, a more constrained project scope might have yielded a more functionally complete application and a potentially more satisfying development experience. Additionally, selecting a familiar technology stack while pushing boundaries in targeted areas could have been strategically wiser than the comprehensive skill expansion I pursued.

However, I maintain that the emphasis on acquiring new professional competencies justified the trade off in project functionality. The confidence gained from achieving substantial progress on ambitious objectives, coupled with the autonomy to modify requirements as needed, created an empowering learning environment that aligned well with the self-guided nature of this professional development course.

### Lessons Learned
Several key lessons can be applied moving forward.

#### Eliminate Intermediate Applications
Rather than developing separate mini-projects for each learning module, I would apply new concepts directly to the main project. This would eliminate the artificial transition expectations and preserve valuable development time.

#### Strategic Recovery Periods
I would incorporate planned catch-up sessions to address the inevitable accumulation of technical debt from ambitious weekly goals. This became particularly evident during the testing stage, where moving forward with incomplete understanding created compounding challenges later in the project.

#### Scope Management
The consistent pattern of achieving 80% completion, while motivating, also resulted in accumulated gaps that required additional time investment in subsequent phases. More realistic weekly objectives might have prevented this technical debt accumulation.  Importantly, this "ambitious pragmatism" approach does not translate effectively to team-based or professional environments where consistent delivery and predictable timelines are essential for collaborative success and client satisfaction.

Despite these potential improvements, I remain convinced that this ambitious, self-directed approach was well-suited to both my learning objectives and the course structure. The combination of substantial skill acquisition, maintained motivation, and meaningful project progress represents a successful professional development outcome.


## Conclusion
<!-- Look to the past, the present, and look to the future. How did this confirm/change your outlook?
What could you do next? -->
### Learning and Development
This project has fundamentally shaped my perspective on both learning and professional development in ways that extend far beyond technical skill acquisition. Reflecting on the experience, I have gained profound appreciation for the structured learning environment that formal coursework provides. Having chosen to pursue a computer science degree rather than self-directed study, this project illuminated the substantial time and effort that independent learning requires while highlighting the efficiency of guided academic instruction.  Paradoxically, the autonomy and control inherent in this self-directed project proved extraordinarily empowering after semesters of rigid requirements and fixed deadlines. Having experienced both approaches to education and development, I will more confidently identify when structured coursework is necessary versus when independent learning and exploration are more appropriate.

### Refined Vision for Small Business Solutions
This experience reinforced my commitment to developing software solutions for small businesses, however, after wrestling with the complexity of this application I can acknowledge that not every small business is a suitable candidate for a custom tailored full stack application.  Working with a real client shifted the focus on my project portfolio building from broad hypothetical audiences toward addressing specific, individual needs.  This client focused approach proved more fulfilling than I expected.  The experience validated serving smaller, well-defined user bases rather than attempting the next big app for mass market.

### Professional Insights and Technical Growth
The "ambitious pragmatism" methodology that emerged during this project revealed important insights about my professional working style. I discovered that intimidating challenges with constrained timeframes provide optimal motivation for my productivity. This approach taught me that attempting goals that initially seem beyond reach triggers a determination to exceed expectations—a valuable self-awareness for future project planning.

Acquiring .NET Core proficiency has expanded my technical versatility significantly. The enterprise-friendly nature of this technology stack, combined with my existing experience in Full Stack Development, Python, Machine Learning, and Systems Programming, positions me as a more attractive, multi-faceted candidate across diverse development environments. Moreover, I found .NET's emphasis on professional, efficient implementation particularly satisfying.

### Key Lessons and Future Applications
This experience highlighted the critical importance of balancing learning objectives with delivery requirements. While educational priorities necessarily emphasized skill acquisition over project completion, future endeavors will benefit from alternating focused learning phases with dedicated implementation periods rather than attempting parallel progress.

Perhaps most significantly, this project generated substantial professional confidence through the experience of independently initiating, managing, and delivering a complex software solution. The accumulated progress reports and comprehensive GitHub repository serve as tangible evidence of sustained achievement. The confidence gained from successfully navigating an ambitious, self-directed technical project represents what I needed most at this stage of my development.

### Looking Forward
Looking forward, I am eager to continue developing this application while focusing on user feedback and iterative improvement rather than simultaneous skill acquisition. This project has established both a technical foundation and a professional methodology that will inform my approach to future software development challenges, particularly those serving the practical needs of growing businesses.

<br> 
<hr> 
<br>

## Project Deliverables

**Code and Documentation**

The complete source code for both the API and frontend application can be accessed in the [GitHub Repository](https://github.com/nathanjh-28/Video-Project-Suite).

**Deployment**

The application's API is deployed on Render.com with the frontend served on Vercel:
* [API link, *video-project-suite.onrender.com*](https://video-project-suite.onrender.com/)
* [React App deployed using Vercel, *video-project-suite.vercel.app*](https://video-project-suite.vercel.app/)

Due to Render.com's free tier limitations, the server requires approximately one minute to initialize from a dormant state. To test the API connection, open the browser's developer console and execute the following code snippet:

```javascript
fetch('/api/test').then(r => r.json()).then(console.log)
```

This command will return a confirmation string indicating successful API connectivity.

**Project Blog**

Comprehensive project planning documentation and weekly progress reports are available on the [Project Blog](https://nathanjh-28.github.io/vp-suite-blog/)

## Learning Resources

<!-- Give a list of resources or articles used in the project. List code or other public products from your project. -->


### Preliminary 

[Full Stack Open](https://fullstackopen.com/)

[Microsoft Learn - Get Started with C#](https://learn.microsoft.com/en-us/training/paths/get-started-c-sharp-part-1/)

### Learning C#

[Giraffe Academy youtube video](https://youtu.be/irBHuMTDsNg?si=-UIfv5ac49m73nTU)

[Create a .NET console application using Visual Studio Code](https://learn.microsoft.com/en-us/dotnet/core/tutorials/with-visual-studio-code)

[Classes and objects tutorial - C#](https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/tutorials/classes)

[Object-Oriented Programming - C#](https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/tutorials/oop )

### Learning Basic Web APIs with .NET Core

[Microsoft Learn - First Web API](https://learn.microsoft.com/en-us/aspnet/core/tutorials/first-web-api)

[Microsoft Learn - Build a Web API ASP.NET Core](https://learn.microsoft.com/en-us/training/modules/build-web-api-aspnet-core/)

[Minimal API Tutorial](https://learn.microsoft.com/en-us/aspnet/core/tutorials/min-web-api)

[Microsoft Learn Back End Development Playlist](https://www.youtube.com/playlist?list=PLdo4fOcmZ0oWunQnm3WnZxJrseIw2zSAk)

### More on .NET Ecosystem

[Dotnet Core Podcast](https://dotnetcore.show/)

[.NET roadmap](https://github.com/milanm/DotNet-Developer-Roadmap)

I purchased the following books and used portions as a reference

[C# 13 and .NET 9 - Modern Cross-Platform Development Fundamentals by Mark J. Price](https://www.amazon.com/13-NET-Cross-Platform-Development-Fundamentals/dp/183588122X)

[Apps and Services with .NET 8 by Mark J. Price](https://www.amazon.com/Apps-Services-NET-enterprise-technologies/dp/183763713X/)

[Tools and Skills for .NET 8 by Mark J. Price](https://www.amazon.com/Tools-Skills-NET-practices-solutions/dp/183763520X/)


### Entity Framework Core - .NET's Object Relational Mapping Tool

[Microsoft Learn Tutorial](https://learn.microsoft.com/en-us/training/modules/persist-data-ef-core/)

Testing with .NET Core and Test Driven Development

I used the Tools and Skills book significantly to understand the concepts.

[xUnit tutorial](https://xunit.net/docs/getting-started/v2/netfx/visual-studio)

### User Authentication and Authorization using JSON Web Tokens

[JWT Authentication with .NET 9 - youtube](https://www.youtube.com/watch?v=6EEltKS8AwA)

[Microsoft Learn - Authentication](https://learn.microsoft.com/en-us/aspnet/core/security/authentication/?view=aspnetcore-9.0)

[Microsoft Learn - JWT](https://learn.microsoft.com/en-us/aspnet/core/security/authentication/configure-jwt-bearer-authentication?view=aspnetcore-9.0)

### React and Material UI

[crash course on Material UI](https://youtu.be/o1chMISeTC0?si=SPX_4bryb_ndvotI)

[React JS Tutorial youtube](https://youtu.be/Ke90Tje7VS0?si=PQYiLUU079rcfXY3)

[Material UI Component Library Documentation](https://mui.com/material-ui/all-components/)

### CI/CD

- [Microsoft Learn - GitHub Actions and .NET (documentation)](https://learn.microsoft.com/en-us/dotnet/devops/github-actions-overview)
- [CI/CD with GitHub Actions - .NET on Azure (Microsoft Learn youtube video)](https://youtu.be/7LkRipTlTzc?si=Wumh9qzlkcKSCI3U)
- [Github's Quickstart Guide](https://docs.github.com/en/actions/get-started/quickstart)

### Docker Resources:
- [.NET language specific guide for Docker](https://docs.docker.com/guides/dotnet/)
- [Microsoft Learn Tutorial: Containerize a .NET app (documentation)](https://learn.microsoft.com/en-us/dotnet/core/docker/build-container)
- [Deploy .NET Apps to Containers - .NET on Azure (youtube video)](https://youtu.be/tpNQpiwJexM?si=4bho8meapu4aEqhq)

### Deployment

[Deploy on Render with a Container Registry](https://render.com/docs/deploying-an-image)

[Containers on GitHub Registry](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-container-registry)

[Deploying on Vercel with Vite](https://vercel.com/docs/frameworks/frontend/vite)



## Project Images

### React Front End App
The following screenshots demonstrate the current state of the deployed React application:

#### Homepage
![homepage](../images/week-10-vps-homepage.png)

#### New Project Form
![homepage](../images/week-10-newproject-form.png)

#### Register Page
![homepage](../images/week-10-register-page.png)

### Design Documentation
Below are wireframes and mockups from the project planning phase that will guide development:

#### Homepage Mock Up
The navbar will be collapsable and include links to the different feature modules.


![Mock Up Homepage](../images/wireframes/navbar.png)

#### Kanban Feature Mock Up
Projects can be viewed in kanban style similar to Trello.

![Mock Up Kanban](../images/wireframes/kanban.png)

#### Reporting Feature Mock Up
Financial health of the video production company can be viewed using customizable charts and graphs.

![Mock Up Reporting](../images/wireframes/reports.png)

#### Project Detail Mock Up
![Mock Up Project Detail](../images/wireframes/detail.png)
