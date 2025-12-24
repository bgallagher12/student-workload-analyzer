# Student Workload Analyzer

**Author:** Brendan Gallagher

## Overview
The Student Workload Analyzer is a Python-based application designed to help students better understand and manage their academic workload. Users can input courses and assignments with due dates and estimated effort, and the system analyzes weekly workload patterns to identify high-stress periods and potential overload.

Rather than acting as a simple task tracker, the application focuses on workload analysis and scheduling insights, helping users make informed decisions about how and when to complete their work.

## Core Features (Planned)
- Create and manage courses and academic tasks
- Assign due dates, estimated hours, and difficulty levels to tasks
- Analyze total workload by week
- Detect weeks that exceed recommended workload thresholds
- Generate suggestions to redistribute flexible tasks before deadlines

## Tech Stack
- **Backend:** Python, FastAPI
- **Database:** PostgreSQL
- **ORM:** SQLAlchemy
- **Migrations:** Alembic
- **Testing:** Pytest
- **Deployment:** TBD (Render or Fly.io)

## Goals
- Practice backend API design and relational data modeling
- Apply business logic to real-world scheduling problems
- Build a project that reflects production-style engineering practices

## Future Improvements
- User authentication
- Calendar export (iCal)
- Notifications or reminders
- Frontend dashboard
