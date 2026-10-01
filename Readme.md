<div align="center">

# Hussain Ali

### Full-Stack Developer · Computer Science Student

**From relational data to real-time interfaces.**

I build applications with Go, TypeScript, and JavaScript, connecting backend logic, meaningful data, and thoughtful user interfaces.

[Projects](#featured-projects) · [Engineering](#engineering-highlights) · [Activity](#github-activity) · [Connect](#connect-with-me)

</div>

---

## About Me

I'm Hussain, a computer science student working across backend and frontend development. My projects include social platforms, interactive dashboards, a bilingual coding study lab, database applications, TCP chat, and browser games.

I enjoy solving the problems behind an application: enforcing permissions, modeling relationships, managing live connections, and keeping interfaces usable as features grow.

My work includes leading a four-person social-network project, with primary ownership of groups and events, the 3D presentation layer, settings, and cross-feature integration.

## Tech Stack & Tools

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)

| Area | Technologies used |
| :--- | :--- |
| Languages | Go · TypeScript · JavaScript · PHP · SQL · C · Java · Python |
| Frontend | React · Next.js · Vite · HTML · CSS · Tailwind CSS · JavaScript ES modules |
| Backend | Go `net/http` · Node.js / Express · PHP / PDO |
| APIs & authentication | HTTP APIs · GraphQL · JWT · cookie-based sessions · bcrypt |
| Databases | SQLite · MySQL · relational schemas · SQL migrations |
| Real-time & networking | Gorilla WebSocket · TCP sockets · goroutines · mutexes |
| Graphics & interaction | Three.js · React Three Fiber · custom SVG charts · Motion |
| Tools & platforms | Git · Docker / Compose · npm · Netlify · GitHub Pages |
| Testing & quality | Go testing · Vitest · ESLint |

## Featured Projects

Selected educational, personal, and team projects, with documented team ownership identified below.

### 01 · [Spacial Network](https://github.com/hussainhht/Spacial-Network)

A social platform combining privacy-aware communities with an interactive space-themed interface.

**Go · Next.js · React · TypeScript · SQLite · WebSocket · Three.js · Docker**

- Public/private groups, invitations, approval-based membership, and event RSVPs, supported by backend authorization and transactional membership updates.
- Private/group messaging and notifications.
- A persistent 3D scene connects planet selection with interface themes and reduced-motion support.

**My role:** Team lead; primary ownership of groups/events, space visuals, settings, and integration.

<a href="https://github.com/hussainhht/Spacial-Network">
  <img src="https://raw.githubusercontent.com/hussainhht/Spacial-Network/main/docs/assets/readme/group-page.png" alt="Spacial Network group page with membership tabs and a space-themed interface" width="100%" />
</a>

### 02 · [Reboot Guild Hall](https://github.com/hussainhht/Reboot-Guild-Hall)

A dark-fantasy dashboard that transforms Reboot01 profile data into a character sheet, project journey, and interactive statistics.

**React · JavaScript · Vite · GraphQL · JWT · SVG · Motion · Netlify**

- Reboot01 sign-in obtains a JWT for authenticated GraphQL requests. A service layer and profile hook fetch the current user, then run six related queries in parallel, with loading, error, and retry states.
- Hand-built SVG visualizations display XP progression, monthly activity, project rankings, audit ratios, and skill radar charts using geometry computed in React components.
- A responsive interface combines level-based character portraits, an interactive project journey, animated panels, and remembered audio preferences.

[Live demo](https://hussainali7.netlify.app/) · [Architecture](https://github.com/hussainhht/Reboot-Guild-Hall#architecture)

<sub>The demo is public; viewing profile data requires your own Reboot01 account.</sub>

<a href="https://github.com/hussainhht/Reboot-Guild-Hall">
  <img src="https://raw.githubusercontent.com/hussainhht/Reboot-Guild-Hall/main/docs/screenshots/dashboard-overview.webp" alt="Reboot Guild Hall dashboard with a character portrait, XP statistics, progression chart, and audit ratio" width="100%" />
</a>

### 03 · [Real-Time Forum](https://github.com/hussainhht/real-time-forum)

A single-page forum with live user presence and private messaging, built by a two-person team using Go and vanilla JavaScript.

**Go · SQLite · Gorilla WebSocket · JavaScript ES Modules · HTML / CSS**

- HTTP handles authentication, posts, comments, message sending, and history; WebSocket events push private messages, presence changes, and registration updates to connected browsers.
- Messages are persisted in SQLite before delivery. Cursor-based history loads older messages in batches of ten, while the chat interface preserves scroll position and shows live unread indicators.
- Cookie-based sessions and bcrypt authentication support a hand-built SPA with hash routing, persistent navigation, and session-aware socket reconnection.

**My role:** Developer alongside team leader **Nawraa Sayed**. My contributions include project foundations, registration validation and password hashing, message-history queries, initial messaging handlers and WebSocket integration, and much of the chat interface and history-loading behavior.

[Architecture](https://github.com/hussainhht/real-time-forum#architecture) · [WebSocket design](https://github.com/hussainhht/real-time-forum#websocket-architecture) · [Team contributions](https://github.com/hussainhht/real-time-forum#team--contributions)

<a href="https://github.com/hussainhht/real-time-forum">
  <img src="https://raw.githubusercontent.com/hussainhht/real-time-forum/main/docs/screenshots/live-chat.png" alt="Two browser sessions showing a private message arriving live without a page refresh" width="100%" />
</a>

<sub>Live messaging between two browser sessions, using fictional demo accounts. The current implementation accepts messages only when the recipient is online.</sub>


### 04 · [Research Publication Tracker](https://github.com/hussainhht/DATABASE-MANAGEMENT-SYSTEMS-05)

A university database project for organizing researchers, publications, authorship, venues, and keywords.

**Go · MySQL · SQL · JavaScript · HTML / CSS**

- Relational modeling with foreign keys, composite keys, and junction tables for authorship and publication keywords.
- CRUD APIs and SQL reports using joins and aggregation, with browser views for data management and reporting.

### 05 · [Shot Share](https://github.com/hussainhht/shot_share)

A PHP/MySQL course project for sharing posts and photos with a community.

**PHP · PDO · MySQL · JavaScript · HTML / CSS**

- Session-based login, password hashing, prepared SQL statements, and owner-controlled post deletion.
- Image uploads, likes, comments, keyword search, and persisted interaction notifications.
- A responsive interface with light and dark themes.

### 06 · [REBOOT Fighting Game](https://github.com/hussainhht/make-your-game)

A browser fighting game with modular gameplay systems and sprite animation.

**JavaScript · HTML / CSS · Browser APIs**

- A `requestAnimationFrame` engine separates updates from rendering and uses elapsed time for gameplay changes.
- Fighter state, hitboxes, stamina, blocking, and timed escape mechanics are organized into separate systems.
- Story/tower modes and browser-stored tower progress.

[Live demo](https://hussainhht.github.io/make-your-game/docs/)

### 07 · [Net-Cat TCP Chat](https://github.com/hussainhht/net-cat)

A concurrent terminal chat server built as a Reboot Coding Institute project.

**Go · TCP · Goroutines · Mutexes · gocui**

- Multiple rooms with message broadcasting, in-memory history replay, and join/leave announcements.
- A goroutine handles each connection, while shared registries use mutexes.
- Chat commands and an experimental terminal administration interface.

### 08 · [Tetris Optimizer](https://github.com/hussainhht/tetris-optimizer)

A command-line solver that packs tetrominoes into the smallest square found within its board-size limit.

**Go · Backtracking · Input validation**

- Validates block dimensions, allowed characters, piece size, connectivity, and separators before normalizing coordinates.
- Starts from an area-based lower bound and tries increasing board sizes.
- Recursively places and removes pieces to find a non-overlapping arrangement.

<details>
<summary><b>More projects and collaborative work</b></summary>

- [ASCII Art Web](https://github.com/hussainhht/ascii-art-web) — a team-built Go web application for text-to-ASCII conversion, selectable banners, themed pages, and text export.
- [ATM Management System](https://github.com/hussainhht/atm-management-system) — an educational C console application with account operations and flat-file persistence.
- [Java Library System](https://github.com/hussainhht/itcs214-projet) — object-oriented book/member management, lending rules, and linked-list storage.
- [Finding Exoplanets](https://github.com/hussainhht/Finding-exoplanets) — a NASA Space Apps team fork containing a Python classification pipeline and Flask interface. My visible contributions include frontend styling and interface refinements.

</details>

## Engineering Highlights

- **Data integrity:** Group membership transitions use SQL transactions and conditional updates to coordinate invitations, requests, and membership records.
- **Application structure:** The social-network backend separates HTTP handlers, domain services, and repositories. Reboot Guild Hall separates API requests, data fetching, derived statistics, and presentation.
- **Real-time integration:** My forum work connects persisted message history with WebSocket-driven delivery and a browser-rendered chat interface, including cursor pagination and incremental UI updates.
- **Connected systems:** My projects span HTTP APIs, GraphQL queries, WebSocket messaging, and raw TCP connections.
- **Visualization fundamentals:** Reboot Guild Hall uses custom SVG charts with computed coordinates, polar geometry, and animated data shapes.
- **Algorithmic problem-solving:** Tetris Optimizer combines strict input validation with recursive placement and an area-based search starting point.
- **Testing and usability:** The social network contains authorization and domain tests; the study lab tests grading and localization. Interface work includes reduced-motion behavior, keyboard interaction, and responsive layouts.

## GitHub Activity

[Public contribution activity](https://github.com/hussainhht?tab=overview) · [All public repositories](https://github.com/hussainhht?tab=repositories)

Language breakdowns are available on each repository. GitHub activity and language percentages include coursework and collaborative work and do not capture all development activity.

## Currently Exploring

My recent projects explore Go service design, transactional workflows, real-time browser interfaces, GraphQL data integration, and custom SVG visualization.

## Connect With Me

[![GitHub](https://img.shields.io/badge/GitHub-hussainhht-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/hussainhht)

Explore the repositories above for source code, setup instructions, and project documentation.
