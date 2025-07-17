---
layout: page
title: Features List
---

## 1. User Authentication and Roles
At the core of this application is the way the user interacts with projects based on the permissions and assignments given.  An admin user will manage these permissions and assignments.

### User Stories


## 2. Projects Module
An admin user may create a project and assign different users to the project.  A project is the main entity of the application and contains important information and will be referenced by subsequent modules.

### User Stories

## 3. Milestones Module and Type Module
Each project will have a status described as a milestone.  Projects can be viewed or filtered based on these status milestones.  For example, "In production", "In edit", or "waiting for payment."

Each project will have a corresponding Type, which will connect it to different templates.

### User Stories

## 4. Tasks Module and Template Tasks
A dynamic list of tasks will be assigned to a project.  Think of these as a Project based To Do list.  The metadata in the task will allow for filtering as well as the crucial aspect of whether the task is complete.

An additional entity will mirror tasks, called Template Tasks and refer to a project type.  When creating a new project of a certain type, all of the tasks assigned to that type will be automatically added to the project.

### User Stories

## 5. Deliverables Module and Template Deliverables
A given project may have multiple deliverables.  For example, a client may receive one shoot day but require a 30 second promotional video in addition to a longer 2 minute video.  Both videos will have the same client, the same project, and will be considered deliverables each.

Just like with template tasks, template deliverables will mirror deliverables and link to a project type.

### User Stories

## 6. Events Module and Template Events
Events will be similar to tasks but contain different information related to time constraints and locations.  An event could be a shoot day or even a meeting with a client to approve plans.  Shoot Days will have shooting schedules attached that can be shared between producers and clients.

Just like with template tasks, template events will mirror events and link to a project type.

### User Stories

## 7. Invoicing Module and Template Invoices
The Invoice entity will keep track of projects invoice status as well as multiple invoices if needed.

Just like with template tasks, template invoices will mirror invoices and link to a project type.

For a detailed list of Features, Epics and Themes [click here]({{ site.baseurl }}/design_pages/features)