<p align="center" >
  <img width=100% height=100% alt="Screenshot 2026-02-10 at 10 00 46 PM" src="https://github.com/user-attachments/assets/8671e48e-1878-45f5-8c22-9eac944cc6f2"/>
</p>

---

# Rolemap 🧭

> Daily quests for landing your dream job.

Rolemap is an AI-powered career planning platform that transforms vague career goals into a structured, gamified, and actionable roadmap.

Users select 2–3 target roles (e.g., Software Engineer, Product Manager), rank dream companies, upload their resume, and connect their GitHub. Rolemap analyzes their current skill set, compares it against real hiring expectations, and generates a personalized visual roadmap with daily and weekly tasks.

Instead of “set it and forget it” career goals, Rolemap builds systems for consistent progress.

---

# ✨ Why Rolemap?

Job preparation often feels overwhelming and unstructured. Rolemap solves this by:

- Analyzing where you are now (Resume Parsing + GitHub)
- Comparing your skills to real job expectations
- Highlighting skill gaps
- Generating clear, executable tasks
- Reinforcing learning with checkpoints
- Gamifying consistency with streaks and points

---

# 🧩 MVP Features

## 1️⃣ Role & Company Selection
- Choose 2–3 target roles
- Select and rank dream companies
- Prioritize focus if multiple roles are selected

## 2️⃣ Resume Upload & Parsing
- Upload PDF or DOCX resume
- Extract:
  - Skills
  - Experience
  - Projects
- Identify missing or underdeveloped skills

## 3️⃣ GitHub Integration
- Connect GitHub account
- Analyze repositories for:
  - Languages used
  - Commit activity & recency
  - Project scope
- Infer actively practiced skills
- Map projects to role expectations

## 4️⃣ Personalized Skill Gap Roadmap
- Visual roadmap with checkpoints
- Highlight missing skills
- Recommend exercises or learning resources
- Adapt roadmap as progress is made

## 5️⃣ Daily & Weekly Tasks
- Generate small, actionable tasks
- Assign deadlines
- Sync with Google Calendar / Apple Calendar
- Notifications & reminders

## 6️⃣ Gamification Layer
- Points system
- Streak tracking
- Leaderboard
- Milestone checkpoints

---

# 🌱 Stretch Goals

- LinkedIn parsing for improved customization
- Company culture & fit analysis
- Skill decay tracking with spaced repetition
- Anonymous forum with intern/full-time insights
- Data-driven insights on skills that mattered in hiring

---

# 🗺️ Development Timeline

| Week | Focus | Frontend | Backend |
|------|--------|----------|----------|
| 1 | Setup & Scope | Next.js + TypeScript + Tailwind setup, layout structure, wireframes | PostgreSQL setup, initial schema (users, roles, skills, roadmaps, tasks), environment config |
| 2 | Design & Data Modeling | High-fidelity Figma designs, onboarding flow, resume upload UI | Resume parsing logic, GitHub API integration, CRUD operations |
| 3–4 | Skill Analysis & Roadmap Engine | Roadmap visualization, skill gap display, dashboard layout | GitHub repository analysis, skill weighting model, roadmap generation algorithm |
| 5–6 | Task System & Gamification | Daily/weekly task views, task completion interactions, streaks & leaderboard UI | Task generation logic, progress tracking, scoring system, leaderboard queries |
| 7–8 | Integration & Polish | UX refinements, responsive design, accessibility improvements | Performance optimization, data validation, security checks, bug fixes |
| 8.5–10 | Demo & Final Prep | Final UI polish, testing | Full integration, demo rehearsal, presentation prep |

---

# 🛠️ Tech Stack

## Frontend
- Next.js (React + TypeScript)
- Tailwind CSS
- Figma (UI/UX design)

## Backend
- Node.js
- PostgreSQL (Supabase or self-hosted)
- Prisma (ORM)

## AI & APIs
- OpenAI API (resume parsing, roadmap & task generation)
- GitHub REST API
- Google Calendar API

## Tools
- GitHub
- VS Code

---

# 📚 Rolemap Learning Resources

To go from zero to building Rolemap.

---

## Frontend (Next.js, React, TypeScript, Tailwind)
- [HTML & CSS Full Course](https://www.youtube.com/watch?v=mU6anWqZJcc) – Covers layout, styling, and responsive basics.
- [JavaScript Crash Course for Beginners](https://www.youtube.com/watch?v=upDLs1sn7g4) – ES6 features included; fundamentals for interactivity.
- [React JS Crash Course](https://www.youtube.com/watch?v=w7ejDZ8SWv8) – Components, state, props, and building UI.
- [TypeScript React Tutorial](https://www.youtube.com/watch?v=WBPrJSw7yQA) – Integrate TypeScript in React projects for type safety.
- [Next.js 13 Tutorial for Beginners](https://www.youtube.com/watch?v=MFuwkrseXVE) – Pages, routing, API routes, and server-side rendering.
- [Tailwind CSS Full Course 2025](https://www.youtube.com/watch?v=dFgzHOX84xQ) – Utility-first CSS framework for fast styling.
- [Figma Tutorial for Beginners](https://www.youtube.com/watch?v=FTFaQWZBqQ8) – Design mockups and high-fidelity UI.

---

## Backend (Node.js, Express, PostgreSQL, Prisma)
- [Node.js Tutorial for Beginners](https://www.youtube.com/watch?v=TlB_eWDSMt4) – Setup, modules, and basic backend concepts.
- [Express.js Crash Course](https://www.youtube.com/watch?v=L72fhGm1tfE) – Routing, middleware, JSON endpoints.
- [PostgreSQL Full Course for Beginners](https://www.youtube.com/watch?v=qw--VYLpxG4) – Tables, queries, CRUD operations.
- [Prisma & PostgreSQL Beginner Tutorial](https://www.youtube.com/watch?v=F56XyD0sopA) – Simplify DB queries, migrations, and type-safe backend code.
- [REST API Crash Course](https://www.youtube.com/watch?v=Q-BpqyOT3a8) – Build API endpoints for frontend integration.
- [GitHub REST API Tutorial](https://www.youtube.com/watch?v=8uG9zLQe9Gk) – Read repos, commits, and languages programmatically.

---

## AI / LLM Integration
- [OpenAI GPT-4 Tutorial](https://www.youtube.com/watch?v=2-CB1Yp3f0k) – Learn API calls in Node.js.
- [LangChain + GPT Tutorial](https://www.youtube.com/watch?v=umqFSSfT7JA) – Build pipelines for parsing and text processing.
- [Resume Parser Tutorial](https://www.youtube.com/watch?v=v3B21U2yGvQ) – Step-by-step example using GPT models.
- [Prompt Engineering Basics](https://www.youtube.com/watch?v=J3WmM6z8qA4) – Learn how to structure prompts for extraction.

---

## Calendar & Notifications Integration
- [Google Calendar API Tutorial](https://www.youtube.com/watch?v=KBrqls4GJ84) – Add events/notifications programmatically.
- [Apple Calendar API Overview](https://developer.apple.com/documentation/eventkit) – iOS/macOS integration guide.

---

## Gamification & UI Extras
- [How to build gamification in JS](https://www.youtube.com/watch?v=k5E2AVpwsko) – Implement points, streaks, and leaderboard logic.
- [React Charts Tutorial](https://www.youtube.com/watch?v=E3z9vA7mrUo) – Visualize roadmap completion and progress.

---

## General Tools
- [VS Code Beginner Tutorial](https://www.youtube.com/watch?v=VqCgcpAypFQ) – IDE setup, extensions, and productivity tips.
- [Git & GitHub Crash Course](https://www.youtube.com/watch?v=RGOj5yH7evk) – Version control, commits, branches, pull requests.

---

## ✅ Suggested Learning Path
1. HTML → CSS → JavaScript  
2. React → TypeScript → Tailwind → Next.js  
3. Node.js → Express → PostgreSQL → Prisma  
4. REST APIs → Frontend integration  
5. OpenAI API + LangChain → Resume parsing & roadmap generation  
6. GitHub API → Fetch repos and activity  
7. Calendar integration → Daily task reminders  
8. Gamification → Points, streaks, leaderboard  
9. Optional: Figma, Charts, Accessibility refinements

---

# 👥 Meet the Team
- Quoc Dung (Tom) Pham
- Siri Kishore Dola
- Jon Montague
- Pranay Chintakunta
