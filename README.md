<div align="center">

# David Novakovic

**Backend Engineer · Full-Stack Developer · Software Engineering Student**

[![GitHub](https://img.shields.io/badge/GitHub-nole78-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nole78)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Novakovic%20David-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/novakovic-david)
[![Email](https://img.shields.io/badge/Email-Contact%20me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:daki.nole@email.com)

</div>

## Profile

Fourth-year Applied Software Engineering student at the Faculty of Technical Sciences, University of Novi Sad, with a GPA of **9.90/10**. I focus on backend engineering, distributed systems, full-stack web applications, and game backend architecture.

I enjoy designing maintainable systems, working with layered and clean architecture, and turning complex domain requirements into reliable software. I have experience collaborating in Agile/Scrum teams using GitHub and Jira.

## Technical Skills

### Languages

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![C%23](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=csharp&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

### Backend and Systems

![.NET](https://img.shields.io/badge/.NET%208-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20APIs-02569B?style=flat-square&logo=swagger&logoColor=white)

### Frontend and Game Development

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)

### Data, Infrastructure, and Workflow

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgresSQL](https://img.shields.io/badge/PostgreSQL-316192?logo=postgresql&logoColor=white)
![Microsoft SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)

## Featured Projects

### Turn-Based RPG — Full-Stack Game

A playable turn-based RPG prototype developed for the **Nordeus Challenge 2026**, built with Unity and ASP.NET Core. The backend is authoritative for combat resolution, while the client reconstructs battles from domain events.

**Highlights**

- Server-authoritative turn-based combat
- Event-driven battle reconstruction for damage, healing, and status effects
- Five-node encounter map with replayable fights
- Move learning and loadout management
- XP-based progression and stat scaling
- Single-slot save and load system
- Modular client architecture built around `GameManager`, `BattleManager`, and `ApiClient`

**Stack:** Unity, C#, ASP.NET Core, .NET 8, REST APIs, ScriptableObject architecture

[![Repository](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/nole78/nordeus-rpg)
[![Gameplay Demo](https://img.shields.io/badge/Gameplay%20Demo-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://youtu.be/XRCgYCd0nDU)

### Esports Tournament Platform

A distributed full-stack platform developed by a team of four students for managing esports teams, tournaments, matches, and player participation.

The system includes a React client, a layered Express API, a MySQL data layer, and a custom Node.js load balancer. Production traffic is routed through the load balancer to multiple backend instances deployed across Render and Railway.

**Highlights**

- Tournament, team, lineup, and player management
- Automated bracket generation and match progression
- JWT authentication and role-based authorization
- Audit logging and administrative dashboards
- Custom load balancer with health monitoring
- Weighted Round Robin, Round Robin, Least Connections, and IP Hash strategies
- Layered architecture, Dependency Injection, Repository Pattern, Result Pattern, and SOLID principles
- N+1 query reduction through bulk retrieval operations

**Stack:** React, TypeScript, Vite, Node.js, Express, MySQL, Docker, Render, Railway, Vercel

[![Repository](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/nole78/esports-tournament-platform)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-000000?style=flat-square&logo=vercel&logoColor=white)](https://odp-c2-s-tim-01.vercel.app)

### Hack2On — Electricity Analytics Platform

A hackathon project for detecting non-technical losses, analyzing electricity consumption, and monitoring grid outages over a large-scale dataset.

**Highlights**

- Non-technical loss analytics and top-offender detection
- Feeder anomaly scoring and classification
- Interactive power-grid visualization
- Real-time and historical outage tracking
- Data-driven dashboards backed by optimized queries

**Stack:** Next.js, React, TypeScript, Tailwind CSS, Leaflet, ASP.NET Core Web API, Dapper, SQL Server

[![Repository](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/nole78/electricity-ntl-detection)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-000000?style=flat-square&logo=vercel&logoColor=white)](https://ntl-detection-system-iota.vercel.app)

### Winery Management System

A team-based .NET application featuring role-based authentication, XML-based persistence, layered architecture, and SOLID-oriented development practices.

[![Repository](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/nole78/ers_T02_tim04)

## Engineering Interests

- Distributed systems and service reliability
- Backend and game server architecture
- Scalable API design
- Clean and layered architecture
- Event-driven systems
- Performance optimization and database design
- System design and cloud deployment

## Current Focus

- Expanding the turn-based RPG project
- Deepening knowledge of distributed-system design patterns
- Building scalable backend architectures
- Preparing for software engineering internships

## Contact

- **Email:** [daki.nole@email.com](mailto:daki.nole@email.com)
- **LinkedIn:** [linkedin.com/in/novakovic-david](https://linkedin.com/in/novakovic-david)
- **GitHub:** [github.com/nole78](https://github.com/nole78)
