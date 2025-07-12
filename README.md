# OpenTask - JIRA-like Task Management System

A full-stack task management system built with .NET 8 Web API backend and React 18 frontend.

## Quick Start

1. Clone the repository
2. Run `docker-compose up -d` to start all services
3. Navigate to `http://localhost:3000` for the frontend
4. API documentation available at `http://localhost:5000/swagger`

## Architecture

- **Backend**: .NET 8 Web API with Entity Framework Core 8
- **Frontend**: React 18 + TypeScript + Vite + Tailwind CSS + shadcn/ui
- **Database**: PostgreSQL 16
- **Authentication**: JWT with role-based access control
- **File Storage**: MinIO (S3-compatible)
- **Observability**: OpenTelemetry + Serilog

## Core Features

1. User Management (register/login, roles, profile management)
2. Project Management (CRUD, member invitations, per-project roles)
3. Issue/Task Management (Bug/Task/Story/Epic types, priorities, assignments)
4. Boards (Scrum & Kanban with drag-and-drop)
5. Sprint Planning (velocity calculation, burndown charts)
6. Comments & Collaboration (threaded comments, @mentions, Markdown)
7. Notifications (real-time WebSockets + email fallback)
8. Activity Logs & Audit Trail
9. Search & Advanced Filters
10. Dashboard & Analytics

## Development Setup

Coming soon...

## Environment Variables

Coming soon...

## API Documentation

Coming soon...
