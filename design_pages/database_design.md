---
layout: page
title: Database Design
---

The database will focus on Users and Projects, linking them together with a many to many relationship.  It is assumed up front that a client may have more than one project and a project may have more than one client.  

Additional modules will reference Projects.  Tasks will reference a specific project as to do items needed for that project.  In addition, events (which are tasks with a time and location), deliverables, and invoices will be associated with a specific project.

## Milestones
An entity called Milestones serves as a customizable list of status points for a given project.  Each milestone will contain placement in a list much like a song in a playlist.  Many milestones may exist across Projects but a Project may only have one milestone at a time.

## Types and Templates
Upon creation of a project, the project will be given a specific type from the Types entity.  This will trigger insertions from mirrored Task, Event, and Deliverable template tables.  The Template tables will contain reusable items that do not contain project specific data but serve to help bootstrap a project.  

For example, if you know you need the client to sign your project agreement for every project, and that you will always need a location scout, you could put those in your template tasks and events and associate them with a project type called photo shoot.  When creating a new project of type photo shoot, the project agreement task adn location scout event are automatically added.  In addition if you have promo video packages where you have a specific price for 3 video package or 12 video package, the pricing can be stored in the template as well as the deliverable entities (each of the videos).

## ER Diagram
![Entity Relationship Diagram]({{ site.baseurl }}/images/erd-version1.png)

[Click here]({{ site.baseurl }}/images/erd-version1.png) to see the diagram larger.
