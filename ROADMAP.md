# Roadmap & Initial Tasks

Milestone 1 — Project setup & auth (2–3 days)
- Initialize repository with monorepo (optional)
- Setup backend skeleton (Express) and DB connection
- Implement auth endpoints (signup/login), JWT tokens / Firebase setup
- Create basic user profile model and endpoint

Milestone 2 — Workout logging (3–5 days)
- Define models: Exercise, Workout, WorkoutExercise, Set
- Create endpoints for creating workouts and adding sets
- Build mobile/web UI for creating and saving a workout

Milestone 3 — History & progress (2–3 days)
- Implement endpoints for querying workouts by date range
- Add chart UI for progress metrics (volume, weight, reps)

Milestone 4 — Schedule & reminders (2 days)
- Add schedule model and reminder notifications (local push for mobile or web notifications)
- UI for weekly plan and reminders

Milestone 5 — Polish, export, deploy (3–5 days)
- CSV/PDF export
- End-to-end tests for critical flows
- Deploy backend (VPS / Heroku / Vercel) and publish mobile app (optional)

Optional future features
- Social / Coach sharing
- Class/Team challenges
- Integration with wearables (Apple Health / Google Fit)
