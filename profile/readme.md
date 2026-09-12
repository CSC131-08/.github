# CSC 131, Section 8

Software engineering coursework for Sacramento State, Fall 2026. This organization holds the source for a client sponsored team project built over the course of the semester.

![SEMESTER](https://img.shields.io/badge/semester-Fall%202026-6b7280?style=flat-square)
![COURSE](https://img.shields.io/badge/course-CSC%20131-1f6feb?style=flat-square)
![UNIVERSITY](https://img.shields.io/badge/Sacramento%20State-043927?style=flat-square)
![TEAM](https://img.shields.io/badge/team-6%20members-8b5cf6?style=flat-square)

---

## About

CSC 131 covers the software development life cycle end to end: requirements elicitation and specification, architectural and detailed design, implementation, testing, and maintenance. Teams work with a real client and deliver a working system by the end of the semester.

## Project

**Waste Collection Survey and Dashboard** for the Sac State Office of Sustainability.

The campus pays a private hauler to empty about 100 dumpsters, and today there is no record of whether each pickup happened or how full the bin was. Drivers will record each pickup on a short survey, and we are building the dashboard the sustainability office uses to see what was serviced, when, how full it was, which scheduled pickups were missed, and what it costs.

Client contacts are Laura Gonzalez, Waste and Sustainability Analyst, and Ryan Todd, Director of Energy and Sustainability.

| Repository | What it holds |
| --- | --- |
| [Overwatch](https://github.com/CSC131-08/Overwatch) | The dashboard application. Deploys to [overwatch.thru.dev](https://overwatch.thru.dev/) |
| [context](https://github.com/CSC131-08/context) | Project background, client requirements, and decisions |
| [meeting-notes](https://github.com/CSC131-08/meeting-notes) | Notes from class sessions and team meetings |

## Team

| Name | Role |
| --- | --- |
| Josh Lemos | Project manager |
| Mohd Mahmodi | Technical lead, infrastructure |
| Connor McKelvey | Frontend |
| Parker Luu | Frontend, design |
| Ali Farooq | Backend |
| Ryan Sharma | Backend |

## Deliverables

| Deliverable | Due | Completed |
| --- | --- | --- |
| Team selection and organization | Sept 10, 2026 | Sept 10, 2026 |
| Requirements and design | TBA | |

## Sprints

Sprints run two weeks, and the team presents its progress to the client and the class at the end of each one.

| Sprint | Presented | Focus |
| --- | --- | --- |
| 1 | Sept 24, 2026 | Survey questions to the client. Dashboard prototype on sample data at a live link. |
| 2 | | |
| 3 | | |
| 4 | | |
| 5 | | |
| 6 | | |

## How we work

We follow Scrum. Work is planned in two week sprints, and each sprint ends with a demo. The team meets Mondays and Wednesdays at 3 PM.

Code changes go on their own branch and are opened as a pull request, so another member looks the work over before it merges into `main`. Merging to `main` deploys the live site automatically, which is why direct pushes are reserved for urgent fixes and get called out in the team channel. Branch names say what the work is, for example `feat/pickup-log` or `fix/date-parsing`.

Documentation stays in the repository next to the code, so requirements, design notes, and diagrams live in one place and change along with what they describe. Design research and references are shared in the team's Discord forums.

## Stack

- React with TypeScript, built with Vite
- Hosted on Cloudflare Pages, deployed from `main`
- Sample data in the repository for Sprint 1, with Supabase planned as the database once real data exists
- Chart, map, and component libraries are chosen at the Sept 16 meeting

---

<sub>Coursework repository.</sub>
