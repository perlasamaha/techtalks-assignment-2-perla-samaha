# Six-Month Learning Roadmap

Built directly from the pattern analysis in `market-research.md`. Priority order: React -> JavaScript/TypeScript mastery -> Node.js/backend -> databases -> Docker/cloud basics -> testing/portfolio polish. 
Each month has a primary focus and a lighter secondary track so skills compound instead of being learned in isolation.

## Month 1: JavaScript & TypeScript Foundations
**Why:** JavaScript appeared in 7/8 listings and TypeScript in 4/8 (48% in the wider market data), the base language layer everything else depends on.
- Deepen core JavaScript (async/await, closures, array/object methods, ES modules)
- Learn TypeScript fundamentals: types, interfaces, generics, converting a small JS project to TS
- Git/GitHub workflow refresher (branches, PRs, merge conflicts), assumed baseline in every listing
- **Milestone:** Convert a small existing JS project to TypeScript

## Month 2: React In Depth
**Why:** React appeared in 7/8 listings and topped the aggregate market data at 53%. This is the single highest-leverage skill in the niche.
- Component architecture, hooks (useState, useEffect, useContext, custom hooks)
- State management patterns (Context API, then a lightweight library like Zustand or Redux Toolkit)
- Routing (React Router), forms, and API integration (fetch/axios)
- Component testing basics with Jest/React Testing Library
- Light Angular literacy pass (concepts, component structure, comparison to React). Angular appeared in 4/8 researched listings, mainly at enterprise/government-style employers in Lebanon and the US, so being able to read and reason about Angular code is worth a few hours even while specializing in React
- **Milestone:** Build a multi-page React app that consumes a public REST API

## Month 3: Node.js & Backend APIs
**Why:** Node.js appeared in 5/8 listings; backend competency is what separates "frontend developer" from "full-stack."
- Node.js + Express fundamentals: routing, middleware, error handling
- Building a REST API with proper structure (controllers/routes/services)
- Authentication basics (JWT, sessions, password hashing)
- Connect the Month 2 React app to a real backend you build yourself
- **Milestone:** Full-stack app with a working auth flow (signup/login/protected routes)

## Month 4: Databases & Data Modeling
**Why:** SQL appeared in 4/8 listings and is a baseline requirement regardless of the specific backend language used.
- Relational database design (PostgreSQL): schemas, relationships, indexes, migrations
- Writing and optimizing SQL queries; ORM basics (Prisma or Sequelize)
- Light exposure to a NoSQL option (MongoDB) since it appeared in a couple of listings
- Integrate a real database into the Month 3 backend, replacing any in-memory/mock data
- **Milestone:** Fully persisted full-stack app (React + Node/Express + PostgreSQL)

## Month 5: Docker, Cloud Basics & Deployment
**Why:** This was the biggest surprise from the research, Docker and cloud familiarity appeared in mid-level listings (4/8 and 6/8 respectively), earlier than commonly assumed for a beginner roadmap.
- Docker fundamentals: Dockerfiles, docker-compose, containerizing the frontend + backend + database
- Deploy a full-stack app to a cloud platform (start with a simpler PaaS like Render/Railway, then try AWS basics: EC2 or Elastic Beanstalk, since AWS was the most common cloud provider in the research)
- Environment variables, basic CI/CD concept (a simple GitHub Actions pipeline that runs tests on push)
- **Milestone:** Deploy the Month 4 project live, containerized, with a basic CI pipeline

## Month 6: Testing, Polish & Job-Readiness
**Why:** Testing tools appeared in 3/8 listings and are consistently mentioned as a responsibility even when not explicit. This month is about closing gaps and making the portfolio presentable.
- Add meaningful test coverage (Jest for backend logic, React Testing Library for components, optionally Cypress for E2E on one project)
- Code cleanup, documentation (README with setup instructions and screenshots), and accessibility pass on all portfolio projects
- Resume, LinkedIn, and GitHub profile polish targeted at the keywords found in the research (React, TypeScript, Node.js, PostgreSQL, Docker, AWS)
- Mock interviews / technical interview prep (data structures & algorithms review, system design basics for full-stack roles)
- **Milestone:** 2-3 polished, deployed, tested portfolio projects + updated resume/LinkedIn ready to apply

## Summary Table

| Month | Focus | Key Output |
|---|---|---|
| 1 | JavaScript + TypeScript | TS-converted mini project |
| 2 | React | Deployed multi-page React app |
| 3 | Node.js / Express APIs | Full-stack app with auth |
| 4 | Databases (SQL) | Persisted full-stack app |
| 5 | Docker + Cloud + CI/CD | Live, containerized deployment |
| 6 | Testing + Job Readiness | Polished portfolio + applications ready |