# Portfolio Plan

Three projects, each designed to prove a cluster of the skills that repeated most often across the researched listings (see `market-research.md`). Together they cover the full stack end-to-end and directly mirror responsibilities mentioned in the job postings (building both frontend and backend, integrating APIs, deploying to the cloud, containerization, and testing).

## Project 1: Full-Stack Task/Project Management App
**Proves:** React, TypeScript, Node.js/Express, PostgreSQL, authentication, CRUD API design

A Trello/Asana-style board where users can create projects, add tasks, assign due dates, and drag tasks between status columns. This directly maps to the "building and maintaining client and server-side applications" responsibility that appeared across nearly every listing, and demonstrates the exact core stack (React + Node + SQL) found in 5+ of the 8 researched listings.
- Frontend: React + TypeScript, drag-and-drop UI, protected routes
- Backend: Node.js/Express REST API, JWT authentication
- Database: PostgreSQL with a proper relational schema (users, projects, tasks)
- Stretch: real-time updates with WebSockets (shows initiative beyond the baseline requirements)

## Project 2: Public API Data Dashboard (Deployed & Containerized)
**Proves:** API integration, data visualization, Docker, cloud deployment, CI/CD basics

A dashboard that pulls data from a public API (e.g., a finance, weather, or open government data API echoing the InsurTech/fintech and government-data listings found in the research) and presents it with charts and filters. This project exists specifically to demonstrate the Month 5 skills: Docker and cloud deployment that the research showed are expected earlier than commonly assumed.
- Frontend: React + a charting library (Recharts/Chart.js), responsive design
- Backend: lightweight Node.js API layer to handle API keys and cache responses
- Fully containerized with Docker Compose (frontend, backend, and a caching layer like Redis)
- Deployed to a cloud platform (AWS or a comparable PaaS) with a basic GitHub Actions CI pipeline that runs tests before deploy

## Project 3: Tested E-Commerce or Booking Mini-Platform
**Proves:** Testing (Jest/Cypress), more advanced backend logic, SQL relationships, code quality

A small e-commerce or booking-style app (product listing -> cart/booking -> checkout flow) with meaningful automated test coverage. This project exists to specifically counter the most common weakness in junior portfolios: little to no testing. Since testing tools appeared in 3/8 listings and "writing unit and integration tests" was a repeated responsibility, this project makes that explicit and visible.
- Backend logic with real business rules (inventory/availability checks, pricing/discount logic) enough complexity to make unit tests meaningful
- Jest tests for backend logic and utility functions
- React Testing Library for key component behavior
- Optional Cypress end-to-end test for the full checkout/booking flow

## How These Map Back to the Research

| Project | Skills Demonstrated | Listings This Echoes |
|---|---|---|
| Task/Project Management App | React, TypeScript, Node.js, PostgreSQL/SQL, Auth | Regional System Integrator (Lebanon), Koniag Government Services (US), GSSTech Group (Dubai) |
| Data Dashboard (Docker + Cloud) | AWS, cloud deployment, CI/CD | Voice AI Lead role (Lebanon), Associated Bank (US), Ledgebrook (US) |
| Tested Booking/E-Commerce Platform | Testing, relational data modeling, Angular familiarity | D4 Insight (Dubai), Times World IT (Dubai), Koniag Government Services (US) |