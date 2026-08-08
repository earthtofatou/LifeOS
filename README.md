# LifeOS

Fullstack personal life management web app — a "life operating system" centralizing tasks, calendar, finances, habits, goals, journal, coursework, and documents into a single coherent platform.

## About

LifeOS was born from a simple observation: managing everyday life today is scattered across multiple tools (Notion for notes, Todoist for tasks, Google Calendar for scheduling, a separate app for budgeting). LifeOS brings these use cases together into a single interface, designed to be fast, clean, and consistent.

This project is being built solo, starting from scratch across the entire stack, with the goal of demonstrating real fullstack development proficiency (React / Node.js / Express / MongoDB) through a complete product rather than a series of isolated exercises.

## Features

- **Authentication** — sign up, sign in, profile management, protected routes
- **Dashboard** — personalized overview of the day
- **Tasks** — full task management with priorities, deadlines, subtasks, tags, and filters
- **Calendar** — day / week / month views, synced with tasks
- **Schedule** — customizable weekly timetable
- **Finances** — income and expense tracking, category budgets, chart visualization
- **Habits** — frequency and streak tracking
- **Goals** — short, medium, and long-term progress tracking
- **Journal** — personal entries with mood tracking
- **Documents** — file storage and organization
- **Notifications** — in-app reminders and alerts
- **Coursework** — tracking of courses, grades, exams, and averages

## Tech stack

**Frontend**
- React
- React Router
- Axios
- Context API
- Tailwind CSS

**Backend**
- Node.js
- Express.js
- MongoDB / Mongoose

**Auth & security**
- JWT (JSON Web Token)
- bcrypt

**File handling**
- Multer

## Architecture

The project follows an MVC (Model-View-Controller) architecture on both sides:

```
frontend/
  src/
    pages/        # Application pages
    components/   # Reusable components
    hooks/        # Custom hooks
    services/     # API calls
    contexts/     # React contexts (global state)
    layouts/      # Layout structures

backend/
  routes/         # API route definitions
  controllers/    # Route business logic
  models/         # Mongoose schemas
  middlewares/    # Middlewares (auth, error handling, etc.)
  services/       # Reusable server-side logic
  utils/          # Utility functions
  config/         # Configuration (database, environment variables)
```

## Project status

Actively in development. Current version: V1 (core features, ahead of future extensions: Pomodoro, Markdown notes, cloud sync, mobile app, AI features).

## Installation

Instructions coming once the backend and frontend foundations are in place.

## License

MIT
