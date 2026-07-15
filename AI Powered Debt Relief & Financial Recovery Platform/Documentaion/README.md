# AI Powered Debt Relief & Financial Recovery Platform

An AI-assisted debt management web application for borrowers to track loans, measure financial health, estimate settlement offers, and generate lender negotiation letters.

## Features

- Authentication with email and password
- Financial dashboard with health score, debt-to-income analysis, payment stress, savings buffer, and surplus tracking
- Loan management with creditor, balance, interest, minimum payment, and overdue-day fields
- Settlement predictor using financial profile, delinquency, interest, and affordability signals
- AI-style negotiation letter generator with saved generation history
- FastAPI backend, React + Vite frontend, SQLite persistence, and Docker Compose deployment

## Project Progress Snapshot

- Core project structure and documentation are in place for the full-stack debt relief platform.
- Backend APIs for authentication, loan management, financial analysis, settlement prediction, and letter generation have been implemented.
- Frontend screens for login, dashboard, settlement planning, and letter generation are included and wired to the API.
- Local persistence is handled through SQLite, and the application can be run locally or via Docker Compose.
- Current status: the MVP features are implemented and runnable; future work can focus on testing, validation, and production deployment hardening.

## Tech Stack

- Backend: Python 3.11, FastAPI, SQLModel, SQLite, JWT auth
- Frontend: React, Vite, CSS
- Deployment: Docker, Docker Compose

## Project Structure

1. Brainstorming & Ideation/
2. Requirement Analysis/
3. Project Design Phase/
4. Project Planning Phase/
5. Project Development Phase/
6.Project Testing/
7.Project Documentation/
8.Project Demonstration/

backend/
  app/
    ai/                 Financial scoring, settlement, and letter logic
    routers/            Auth, user, loan, analysis, settlement endpoints
frontend/
  src/
    components/         Login, dashboard, settlement, and letter screens
docker-compose.yml      Full-stack local deployment
requirements.txt        Backend dependencies
.env.example            Environment variable template

