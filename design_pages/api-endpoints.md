---
layout: page
title: API Endpoints
permalink: "/api-endpoints/"

---

### Resource: User
This manages the user permissions and authorization.

| Method | Route                | Description                | Auth Required | Request Body Example                          | Response Example                              | Notes                    |
| ------ | -------------------- | -------------------------- | ------------- | --------------------------------------------- | --------------------------------------------- | ------------------------ |
| GET    | `api/`      | Home Page Data          | No            | –                                             | `[ {  }, ... ]` |      |
| POST    | `api/login` | Get a client by ID        | No            | –                                             | `{ , ... }`     |                          |
| POST   | `api/signup`      | Create a new client       | No           | `{  }` | `{ }`     |  |
|   POST | `api/logout` | Update an existing client | Yes           | `{  }`                  | `{ }`    |          |



### Resource: Client
These routes will manage the clienty entity which is referenced by all other entities

| Method | Route                | Description                | Auth Required | Request Body Example                          | Response Example                              | Notes                    |
| ------ | -------------------- | -------------------------- | ------------- | --------------------------------------------- | --------------------------------------------- | ------------------------ |
| GET    | `/api/clients`      | Get all clients           | Yes            | –                                             | `[ {  }, ... ]` |      |
| GET    | `/api/clients/{id}` | Get a client by ID        | Yes            | –                                             | `{ , ... }`     |                          |
| POST   | `/api/clients`      | Create a new client       | Yes           | `{  }` | `{ }`     |  |
| PUT    | `/api/clients/{id}` | Update an existing client | Yes           | `{  }`                  | `{ }`    |          |
| DELETE | `/api/clients/{id}` | Delete a client           | Yes           | –                                             | `204 No Content`                              |        |

### Resource: Client - Projects
Clients may have more than one project and these routes manage the Client-Project entities.

| Method | Route                | Description                | Auth Required | Request Body Example                          | Response Example                              | Notes                    |
| ------ | -------------------- | -------------------------- | ------------- | --------------------------------------------- | --------------------------------------------- | ------------------------ |
| GET    | `/api/clients/{id}/projects`      | Get all projects           | Yes            | –                                             | `[ {  }, ... ]` |      |
| GET    | `/api/clients/{id}/projects/{id}` | Get a project by ID        | Yes            | –                                             | `{ , ... }`     |                          |
| POST   | `/api/clients/{id}/projects`      | Create a new project       | Yes           | `{  }` | `{ }`     |  |
| PUT    | `/api/clients/{id}/projects/{id}` | Update an existing project | Yes           | `{  }`                  | `{ }`    |          |
| DELETE | `/api/clients/{id}projects/{id}` | Delete a project           | Yes           | –                                             | `204 No Content`                              |        |

### Resource : Client - Projects - Task
Client-Projects can have more than one task and these routes manage the tasks.

| Method | Route                | Description                | Auth Required | Request Body Example                          | Response Example                              | Notes                    |
| ------ | -------------------- | -------------------------- | ------------- | --------------------------------------------- | --------------------------------------------- | ------------------------ |
| GET    | `/api/clients/{id}/projects/{id}/tasks`      | Get all tasks           | Yes            | –                                             | `[ {  }, ... ]` |      |
| GET    | `/api/clients/{id}/projects/{id}/tasks/{id}` | Get a task by ID        | Yes            | –                                             | `{ , ... }`     |                          |
| POST   | `/api/clients/{id}/projects/{id}/tasks`      | Create a new task       | Yes           | `{  }` | `{ }`     |  |
| PUT    | `/api/clients/{id}/projects/{id}/tasks/{id}` | Update an existing task | Yes           | `{  }`                  | `{ }`    |          |
| DELETE | `/api/clients/{id}projects/{id}/tasks/{id}` | Delete a task           | Yes           | –                                             | `204 No Content`                              |        |

### Resource : Client - Projects - Event
Client-Projects can have more than one events and these routes manage the events.

| Method | Route                | Description                | Auth Required | Request Body Example                          | Response Example                              | Notes                    |
| ------ | -------------------- | -------------------------- | ------------- | --------------------------------------------- | --------------------------------------------- | ------------------------ |
| GET    | `/api/clients/{id}/projects/{id}/events`      | Get all events           | Yes            | –                                             | `[ {  }, ... ]` |      |
| GET    | `/api/clients/{id}/projects/{id}/events/{id}` | Get a event by ID        | Yes            | –                                             | `{ , ... }`     |                          |
| POST   | `/api/clients/{id}/projects/{id}/events`      | Create a new event       | Yes           | `{  }` | `{ }`     |  |
| PUT    | `/api/clients/{id}/projects/{id}/events/{id}` | Update an existing event | Yes           | `{  }`                  | `{ }`    |          |
| DELETE | `/api/clients/{id}projects/{id}/events/{id}` | Delete a event           | Yes           | –                                             | `204 No Content`                              |        |

### Resource : Client - Projects - Deliverable
Client-Projects can have more than one deliverable and these routes manage the deliverables.


| Method | Route                | Description                | Auth Required | Request Body Example                          | Response Example                              | Notes                    |
| ------ | -------------------- | -------------------------- | ------------- | --------------------------------------------- | --------------------------------------------- | ------------------------ |
| GET    | `/api/clients/{id}/projects/{id}/deliverable`      | Get all clients           | Yes            | –                                             | `[ {  }, ... ]` |      |
| GET    | `/api/clients/{id}/projects/{id}/deliverable/{id}` | Get a client by ID        | Yes            | –                                             | `{ , ... }`     |                          |
| POST   | `/api/clients/{id}/projects/{id}/deliverable`      | Create a new client       | Yes           | `{  }` | `{ }`     |  |
| PUT    | `/api/clients/{id}/projects/{id}/deliverable/{id}` | Update an existing client | Yes           | `{  }`                  | `{ }`    |          |
| DELETE | `/api/clients/{id}projects/{id}/deliverable/{id}` | Delete a client           | Yes           | –                                             | `204 No Content`                              |        |

### Resource : Client - Projects - Invoice
Client-Projects can have more than one invoice and these routes manage the invoices.

| Method | Route                | Description                | Auth Required | Request Body Example                          | Response Example                              | Notes                    |
| ------ | -------------------- | -------------------------- | ------------- | --------------------------------------------- | --------------------------------------------- | ------------------------ |
| GET    | `/api/clients/{id}/projects/{id}/invoices`      | Get all clients           | Yes            | –                                             | `[ {  }, ... ]` |      |
| GET    | `/api/clients/{id}/projects/{id}/invoices/{id}` | Get a client by ID        | Yes            | –                                             | `{ , ... }`     |                          |
| POST   | `/api/clients/{id}/projects/{id}/invoices`      | Create a new client       | Yes           | `{  }` | `{ }`     |  |
| PUT    | `/api/clients/{id}/projects/{id}/invoices/{id}` | Update an existing client | Yes           | `{  }`                  | `{ }`    |          |
| DELETE | `/api/clients/{id}projects/{id}/invoices/{id}` | Delete a client           | Yes           | –                                             | `204 No Content`                              |        |

### Resource : Task
A producer or business owner has the ability to view and add tasks outside of client filtering.

| Method | Route                | Description                | Auth Required | Request Body Example                          | Response Example                              | Notes                    |
| ------ | -------------------- | -------------------------- | ------------- | --------------------------------------------- | --------------------------------------------- | ------------------------ |
| GET    | `/api/tasks`      | Get all tasks           | Yes            | –                                             | `[ {  }, ... ]` |      |
| GET    | `/api/tasks/{id}` | Get a task by ID        | Yes            | –                                             | `{ , ... }`     |                          |
| POST   | `/api/tasks`      | Create a new task       | Yes           | `{  }` | `{ }`     |  |
| PUT    | `/api/tasks/{id}` | Update an existing task | Yes           | `{  }`                  | `{ }`    |          |
| DELETE | `/api/tasks/{id}` | Delete a task           | Yes           | –                                             | `204 No Content`                              |        |

### Resource : Event
A producer or business owner has the ability to view and add events outside of client filtering.

| Method | Route                | Description                | Auth Required | Request Body Example                          | Response Example                              | Notes                    |
| ------ | -------------------- | -------------------------- | ------------- | --------------------------------------------- | --------------------------------------------- | ------------------------ |
| GET    | `/api/events`      | Get all events           | Yes            | –                                             | `[ {  }, ... ]` |      |
| GET    | `/api/events/{id}` | Get an event by ID        | Yes            | –                                             | `{ , ... }`     |                          |
| POST   | `/api/events`      | Create a new event       | Yes           | `{  }` | `{ }`     |  |
| PUT    | `/api/events/{id}` | Update an existing event | Yes           | `{  }`                  | `{ }`    |          |
| DELETE | `/api/event/{id}` | Delete an event           | Yes           | –                                             | `204 No Content`                              |        |

### Resource : Deliverable
A producer or business owner has the ability to view and add deliverables outside of client filtering.

| Method | Route                | Description                | Auth Required | Request Body Example                          | Response Example                              | Notes                    |
| ------ | -------------------- | -------------------------- | ------------- | --------------------------------------------- | --------------------------------------------- | ------------------------ |
| GET    | `/api/deliverables`      | Get all deliverables           | Yes            | –                                             | `[ {  }, ... ]` |      |
| GET    | `/api/deliverables/{id}` | Get a deliverable by ID        | Yes            | –                                             | `{ , ... }`     |                          |
| POST   | `/api/deliverables`      | Create a new deliverable       | Yes           | `{  }` | `{ }`     |  |
| PUT    | `/api/deliverables/{id}` | Update an existing deliverable | Yes           | `{  }`                  | `{ }`    |          |
| DELETE | `/api/deliverable/{id}` | Delete a deliverable           | Yes           | –                                             | `204 No Content`                              |        |

### Resource : Invoice
A producer or business owner has the ability to view and add invoices outside of client filtering.

| Method | Route                | Description                | Auth Required | Request Body Example                          | Response Example                              | Notes                    |
| ------ | -------------------- | -------------------------- | ------------- | --------------------------------------------- | --------------------------------------------- | ------------------------ |
| GET    | `/api/invoices`      | Get all invoices           | Yes            | –                                             | `[ {  }, ... ]` |      |
| GET    | `/api/invoices/{id}` | Get a invoice by ID        | Yes            | –                                             | `{ , ... }`     |                          |
| POST   | `/api/invoices`      | Create a new invoice       | Yes           | `{  }` | `{ }`     |  |
| PUT    | `/api/invoices/{id}` | Update an existing invoice | Yes           | `{  }`                  | `{ }`    |          |
| DELETE | `/api/invoice/{id}` | Delete a invoice           | Yes           | –                                             | `204 No Content`                              |        |

### Resource Templates
TBD - entities relating to template tasks, events, and deliverables.