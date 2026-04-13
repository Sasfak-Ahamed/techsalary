# TechSalary LK

Community-driven tech salary transparency platform for Sri Lanka.

## Team Members
- Sasfak Ahamed — Frontend + BFF Service
- Member 2 — Database Schema + Identity Service
- Member 3 — Salary Service + Vote Service
- Member 4 — Search Service + Stats Service + Kubernetes

## Tech Stack
- Frontend: Next.js, Tailwind CSS
- Backend: Python, Flask
- Database: PostgreSQL
- Containerization: Docker
- Orchestration: Kubernetes (AKS on Azure)

## Architecture
Microservices architecture with 7 independent services
deployed on a single-node Kubernetes cluster on Azure.

## How to Run
\`\`\`
cd services/backend
docker compose up --build
\`\`\`