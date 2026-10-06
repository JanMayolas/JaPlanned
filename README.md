<p align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=8B5E3C&height=200&section=header&text=JaPlanned%20%E2%98%95&fontSize=50&fontColor=FFF8F0&animation=fadeIn" width="100%" />

</p>

<p align="center">

  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Backend-8B5E3C?style=for-the-badge&logo=server&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-8B5E3C?style=for-the-badge&logo=database&logoColor=white" />

</p>

---

# ☕ JaPlanned

**JaPlanned** is a web-based productivity and planning application that combines calendars, task management, time management, Kanban boards, and visual planning into a single workspace.

The project is designed around the idea of having the tools needed to organize work and time in one place, without making the interface unnecessarily complicated.

JaPlanned combines ideas from applications such as calendars, Pomodoro timers, To-Do applications, Trello, and Excalidraw into a single custom-built application.

The project is being developed from scratch as an educational project to learn how a complete web application works across the **frontend, backend, and database**.

## The website URL:

# Coming soon

---

## 📸 Preview

<p align="center">

  <img src="JaPlanned/assets/images/JaPlanned-Preview.png" width="80%" />

</p>

---

## ✨ Overview

JaPlanned is being developed as a hands-on project to understand how different parts of a modern web application work together.

The project explores:

* Calendar management
* Task management
* To-Do lists
* Pomodoro timers
* Countdown timers
* Digital clock functionality
* Kanban boards
* Drag and drop interfaces
* Visual planning
* User accounts
* Authentication
* Backend APIs
* SQL databases
* Persistent user data
* Frontend and backend communication

The application is intentionally being built without a large frontend framework so that the underlying browser APIs, application logic, backend communication, and database architecture remain visible and understandable.

---

## ☕ Design

JaPlanned uses a warm visual style inspired by the same color palette used in CoffeeDocs, while introducing a different visual identity.

The interface is built around:

* Coffee-inspired brown and cream tones
* Glassmorphism
* Transparent surfaces
* Soft blur effects
* Subtle shadows
* Smooth animations
* Rounded interfaces
* Minimal layouts
* Clear visual hierarchy
* Simple and understandable controls

The goal is to create an interface that feels modern and lightweight while keeping the application easy to understand.

The visual style combines the warm colors of CoffeeDocs with a more modern glass-based interface.

---

## 🛠️ Planned Features

### Calendar

The calendar will provide a visual way to organize events, tasks, and important dates.

Planned functionality includes:

* Monthly calendar view
* Event creation
* Event editing
* Event deletion
* Date-based task organization
* Integration with other JaPlanned features

### Tasks

JaPlanned will include a task management system for organizing everyday work.

Planned functionality includes:

* Create tasks
* Edit tasks
* Delete tasks
* Mark tasks as completed
* Task priorities
* Task dates
* Task organization

### Timer

The timer system will combine several time-management tools.

Planned functionality includes:

* Pomodoro timer
* Countdown timer
* Stopwatch
* Digital clock
* Custom timer durations
* Timer controls

### Boards

JaPlanned will include a Kanban-style board inspired by applications such as Trello.

Planned functionality includes:

* Create boards
* Create columns
* Create cards
* Move cards between columns
* Drag and drop
* Edit cards
* Delete cards
* Persistent board data

### Visual Canvas

A visual planning system inspired by applications such as Excalidraw is also being considered.

Possible functionality includes:

* Free drawing
* Shapes
* Text
* Lines
* Basic object manipulation
* Canvas persistence

This feature will depend on the complexity of implementing a reliable drawing system.

---

## 👤 User Accounts

JaPlanned will include user accounts so that application data can be stored and associated with individual users.

Planned functionality includes:

* User registration
* User login
* User logout
* Authentication
* User data management
* Persistent user data

User-specific application data will be stored in the database rather than only inside the browser.

---

## 🗄️ Backend & Database

Unlike CoffeeDocs, JaPlanned will include a backend and SQL database.

The backend will primarily be responsible for:

* User authentication
* Login and logout
* User registration
* Database communication
* Storing user data
* Loading user data
* Updating user data
* API endpoints
* Server-side validation

The SQL database will store information such as:

* Users
* Tasks
* Calendar events
* Boards
* Columns
* Cards
* User settings
* Other persistent application data

The frontend will communicate with the backend through API requests.

The backend will then communicate with the SQL database when persistent data needs to be created, retrieved, updated, or deleted.

---

## 📁 Project Structure

The final structure is still being designed as the application develops.

A possible structure is:

```text
JaPlanned/
│
├── frontend/
│   │
│   ├── assets/
│   │   ├── fonts/
│   │   ├── icons/
│   │   └── images/
│   │
│   ├── style/
│   │   ├── main.css
│   │   ├── calendar.css
│   │   ├── timer.css
│   │   ├── tasks.css
│   │   ├── boards.css
│   │   └── themes.css
│   │
│   ├── js/
│   │   ├── app.js
│   │   ├── calendar.js
│   │   ├── timer.js
│   │   ├── tasks.js
│   │   ├── boards.js
│   │   ├── auth.js
│   │   └── ui.js
│   │
│   └── index.html
│
├── backend/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   ├── database/
│   └── server.js
│
├── database/
│   └── schema.sql
│
└── README.md
```

The final architecture may change as the project develops.

The goal is to keep each part of the application separated by responsibility rather than placing the entire application into a small number of large files.

---

## 🧱 Technologies

| Technology     | Purpose                                                        |
| -------------- | -------------------------------------------------------------- |
| **HTML5**      | Application structure                                          |
| **CSS3**       | Layout, styling, themes and animations                         |
| **JavaScript** | Frontend logic, DOM manipulation and application functionality |
| **Backend**    | Authentication, API and server-side logic                      |
| **SQL**        | Persistent application and user data                           |
| **Git**        | Version control                                                |
| **GitHub**     | Repository and project management                              |
| **VS Code**    | Development environment                                        |

The exact backend technology and SQL database are still being decided.

---

## 🧠 What I Am Learning

JaPlanned is designed to go beyond frontend development and explore how a complete web application works.

Some of the main concepts explored in the project are:

### Frontend architecture

Organizing a larger JavaScript application into separate modules and responsibilities.

### DOM manipulation

Working directly with HTML elements using JavaScript.

### Events

Using browser events such as:

* `click`
* `input`
* `change`
* `submit`
* `drag`
* `drop`
* `DOMContentLoaded`

### Application state

Managing information such as:

* Current user
* Tasks
* Events
* Timer state
* Selected board
* Board cards
* Application settings

### API communication

The frontend will communicate with the backend using HTTP requests.

The backend will process those requests and interact with the database when necessary.

### Authentication

Learning how user registration, login, logout, sessions, and protected application data work.

### SQL

Learning how structured application data can be stored and retrieved from a relational database.

### Backend architecture

Understanding how routes, controllers, middleware, authentication, and database operations work together.

---

## 🚧 Roadmap

### Phase 1 — Interface

* [ ] Basic project structure
* [ ] Main application layout
* [ ] Header
* [ ] Sidebar
* [ ] Dashboard
* [ ] Glassmorphism design
* [ ] Coffee-inspired color palette
* [ ] Animations
* [ ] Responsive interface
* [ ] Dark theme

### Phase 2 — Tasks

* [ ] Create tasks
* [ ] Edit tasks
* [ ] Delete tasks
* [ ] Complete tasks
* [ ] Task priorities
* [ ] Task dates
* [ ] Task filtering

### Phase 3 — Calendar

* [ ] Calendar interface
* [ ] Monthly view
* [ ] Create events
* [ ] Edit events
* [ ] Delete events
* [ ] Connect tasks with dates

### Phase 4 — Timer

* [ ] Digital clock
* [ ] Countdown timer
* [ ] Stopwatch
* [ ] Pomodoro timer
* [ ] Custom timer settings
* [ ] Timer notifications

### Phase 5 — Boards

* [ ] Create boards
* [ ] Create columns
* [ ] Create cards
* [ ] Edit cards
* [ ] Delete cards
* [ ] Drag and drop
* [ ] Persistent board data

### Phase 6 — Backend

* [ ] Backend server
* [ ] API structure
* [ ] User registration
* [ ] User login
* [ ] User logout
* [ ] Authentication
* [ ] Protected routes
* [ ] Server-side validation

### Phase 7 — Database

* [ ] SQL database
* [ ] User table
* [ ] Task table
* [ ] Event table
* [ ] Board tables
* [ ] User settings
* [ ] Database relationships
* [ ] CRUD operations

### Phase 8 — Visual Canvas

* [ ] Canvas system
* [ ] Drawing
* [ ] Shapes
* [ ] Text
* [ ] Object manipulation
* [ ] Canvas persistence

The visual canvas will only be implemented if it can be integrated without making the application unnecessarily complex.

---

## 📸 Screenshots

<p align="center">

  <img src="JaPlanned/assets/images/JaPlanned-Preview.png" width="80%" />

</p>

More screenshots will be added as the interface evolves.

---

## 📝 Development Notes

JaPlanned is being developed progressively rather than all at once.

The development process follows:

```text
HTML
  ↓
CSS
  ↓
JavaScript
  ↓
Frontend Logic
  ↓
Backend
  ↓
SQL Database
  ↓
Testing
  ↓
Refactoring
  ↓
New Features
```

The frontend will be developed first so that the main interface and application functionality can be established before introducing the backend and database.

Once the frontend structure is stable, the backend will be introduced to handle authentication and persistent data.

The SQL database will then be connected to the backend to allow user-specific information to be stored and retrieved.

The project is intentionally being developed progressively so that each layer of the application can be understood before adding the next one.

---

## 🎯 Project Goal

The main goal of JaPlanned is to understand how to build a complete web application rather than simply creating another frontend project.

The project combines several different types of functionality into one application:

```text
HTML
  ↓
CSS
  ↓
JavaScript
  ↓
DOM
  ↓
Application State
  ↓
API
  ↓
Backend
  ↓
Authentication
  ↓
SQL
  ↓
Persistent User Data
```

Through JaPlanned, I am learning how the frontend, backend, authentication system, and database communicate with each other to create a complete web application.

---

## 👨‍💻 Developer

Built as a personal educational project by **Jan Mayolas**.

The project is continuously evolving as I learn more about frontend development, backend architecture, databases, authentication, and full-stack web development.

---

## 📜 License

JaPlanned is an educational project.

You are free to clone, study, modify, and experiment with the project.

---

<p align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=8B5E3C&height=150&section=footer&fontColor=FFF8F0" width="100%" />

</p>
