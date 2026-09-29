<div align="center">

# Hussain Ali

### Full-Stack Developer · Computer Science Student

**From relational data to real-time interfaces.**

I build web applications with Go, TypeScript, and JavaScript, with a focus on backend logic, connected user experiences, and practical problem-solving.

[Featured projects](#featured-projects) · [Engineering highlights](#engineering-highlights) · [GitHub activity](#github-activity) · [Connect](#connect-with-me)

</div>

---

## About Me

I'm Hussain, a computer science student working across backend and frontend development. My projects include social platforms, a bilingual coding study lab, relational data applications, TCP chat, and browser games.

I enjoy working through the details that make an application function: how permissions are enforced, how data relationships are modeled, how live events reach users, and how the interface stays usable as features grow.

My recent work includes leading a four-person social-network project, with primary ownership of groups and events, the 3D presentation layer, settings, and cross-feature integration.

## Tech Stack & Tools

**Core languages**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)

Also used in coursework and other projects: **C, Java, Python, and SQL**.

| Area | Technologies used |
| :--- | :--- |
| Frontend | React · Next.js · Vite · HTML · CSS · Tailwind CSS |
| Backend | Go `net/http` · Node.js / Express · PHP / PDO · Python HTTP server |
| Databases | SQLite · MySQL · relational schemas · SQL migrations |
| Real-time & networking | Gorilla WebSocket · TCP sockets · goroutines · mutexes |
| Graphics & interaction | Three.js · React Three Fiber · GSAP practice |
| Tools & testing | Git · Docker / Compose · npm · Go testing · Vitest |

## Featured Projects

These are selected educational, personal, and team projects. Descriptions reflect the implementations in their public repositories; team ownership is identified where documented.

### 01 · [Spacial Network](https://github.com/hussainhht/Spacial-Network)

A social platform combining privacy-aware communities with an interactive space-themed interface.

**Go · Next.js · React · TypeScript · SQLite · WebSocket · Three.js · Docker**

- Public/private groups, invitations, approval-based membership, and event RSVPs, supported by backend authorization and transactional membership updates.
- The team application includes private/group messaging and notifications; a persistent 3D scene connects planet selection with interface themes and reduced-motion support.

**My role:** Team lead; primary ownership of groups/events, space visuals, settings, and integration.

<a href="https://github.com/hussainhht/Spacial-Network">
  <img src="https://raw.githubusercontent.com/hussainhht/Spacial-Network/main/docs/assets/readme/group-page.png" alt="Spacial Network group page with membership tabs and a space-themed interface" width="100%" />
</a>

### 02 · [Real-Time Forum](https://github.com/hussainhht/real-time-forum)

A forum and messaging application served by a Go backend with a vanilla JavaScript SPA.

**Go · SQLite · Gorilla WebSocket · JavaScript · HTML / CSS**

- Cookie-based sessions and bcrypt password hashing; ownership checks for post and comment changes.
- Persisted private messages, presence updates, cursor-based history pagination, and client reconnection with exponential backoff.
- A custom hash router and modular frontend features support navigation without a frontend framework.

### 03 · [ITCS333 Midterm Lab](https://github.com/hussainhht/itcs333-study/tree/main/itcs333-midterm-lab)

A local Arabic/English study application for learning HTML, CSS, and PHP through exercises and code execution.

**React · TypeScript · Vite · Express · Monaco Editor · PHP CLI · i18next · Vitest**

- A code editor with sandboxed HTML/CSS previews and actual PHP execution through a local backend, with filename validation, execution timeouts, and output limits.
- Arabic/English switching with RTL/LTR layouts; browser-stored progress, rule-based exercise grading, and a timed mock exam.
- Test suites cover translation completeness, grading, preview generation, and PHP runner behavior.

### 04 · [Research Publication Tracker](https://github.com/hussainhht/DATABASE-MANAGEMENT-SYSTEMS-05)

A university database project for organizing researchers, publications, authorship, venues, and keywords.

**Go · MySQL · SQL · JavaScript · HTML / CSS**

- Relational modeling with foreign keys, composite keys, and junction tables for authorship and publication keywords.
- CRUD APIs and SQL reports using joins and aggregation, with browser views for data management and reporting.

### 05 · [Shot Share](https://github.com/hussainhht/shot_share)

A PHP/MySQL course project for sharing posts and photos with a community.

**PHP · PDO · MySQL · JavaScript · HTML / CSS**

- Session-based login, password hashing, prepared SQL statements, and owner-controlled post deletion.
- Image uploads, likes, comments, keyword search, and persisted interaction notifications, presented through a responsive light/dark interface.

### 06 · [REBOOT Fighting Game](https://github.com/hussainhht/make-your-game)

A browser fighting-game project with modular gameplay systems and sprite animation.

**JavaScript · HTML / CSS · Browser APIs**

- A `requestAnimationFrame` engine separates updates from rendering and uses elapsed time for gameplay changes.
- Fighter state, hitboxes, stamina, blocking, and timed escape mechanics are organized into separate systems, with story/tower modes and browser-stored tower progress.

[Open live demo](https://hussainhht.github.io/make-your-game/docs/)

### 07 · [Net-Cat TCP Chat](https://github.com/hussainhht/net-cat)

A concurrent terminal chat server built as a Reboot Coding Institute project.

**Go · TCP · Goroutines · Mutexes · gocui**

- Multiple rooms with message broadcasting, in-memory history replay, and join/leave announcements.
- A goroutine handles each connection; shared registries use mutexes, with chat commands and an experimental terminal administration interface.

### 08 · [Tetris Optimizer](https://github.com/hussainhht/tetris-optimizer)

A command-line solver that packs tetrominoes into the smallest square found within its board-size limit.

**Go · Backtracking · Input validation**

- Validates block dimensions, allowed characters, piece size, connectivity, and separators before normalizing coordinates.
- Starts from an area-based lower bound, tries increasing board sizes, and recursively places/removes pieces to find a non-overlapping arrangement.

<details>
<summary><b>More projects and collaborative work</b></summary>

- [ASCII Art Web](https://github.com/hussainhht/ascii-art-web) — a team-built Go web application for text-to-ASCII conversion, selectable banners, themed pages, and text export.
- [ATM Management System](https://github.com/hussainhht/atm-management-system) — an educational C console application with account operations and flat-file persistence.
- [Java Library System](https://github.com/hussainhht/itcs214-projet) — object-oriented book/member management, lending rules, and linked-list storage.
- [Finding Exoplanets](https://github.com/hussainhht/Finding-exoplanets) — a NASA Space Apps team fork containing a Python classification pipeline and Flask interface. My visible contributions include frontend styling and interface refinements.

</details>

## Engineering Highlights

- **Business rules with data integrity:** Group membership transitions use SQL transactions and conditional updates to coordinate invitations, requests, and membership records.
- **Application structure:** The social-network backend separates HTTP handlers, domain services, and repositories, with frontend features organized by domain.
- **Networked application fundamentals:** My project work spans HTTP APIs, WebSocket messaging, and raw TCP connections, including connection lifecycle and shared-state coordination.
- **Testing and usability:** The social network contains authorization and domain tests; the study lab tests grading and localization. The 3D interface includes reduced-motion behavior and an option to disable rendering.

## GitHub Activity

[Public contribution activity](https://github.com/hussainhht?tab=overview) · [All public repositories](https://github.com/hussainhht?tab=repositories)

Language breakdowns are available on each repository. GitHub activity and language percentages reflect the repositories GitHub counts, including coursework and collaborative work, and do not capture all development activity.

## Currently Exploring

Building on my recent social-network work, I'm deepening my understanding of Go service design, transactional workflows, and accessible 3D interfaces, alongside tests for authorization and event-driven behavior.

## Connect With Me

[![GitHub](https://img.shields.io/badge/GitHub-hussainhht-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/hussainhht)

Explore the repositories above for source code, setup instructions, and project documentation.
