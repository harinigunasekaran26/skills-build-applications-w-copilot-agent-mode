# Gym Tracker — Student Edition

A lightweight gym tracker designed for students to log workouts, track progress, and maintain workout schedules. Built to be mobile-first (React Native + Expo recommended) with a Node.js backend.

MVP features
- Email + Google sign-in
- Create and log workouts (exercises, sets, weight, reps, duration)
- Workout history and progress charts
- Weekly schedule and reminders
- Export workout history (CSV)

Recommended stack
- Frontend: React Native + Expo (mobile) or React + PWA
- Backend: Node.js + Express (or Next.js API)
- Database: PostgreSQL (or Firebase for managed option)
- Charts: Recharts / Victory / Chart.js
- Auth: Firebase Auth or OAuth (Google) + email/password

Getting started (local)
1. Clone the repo
2. For server:
   - cd server
   - npm install
   - configure .env (DATABASE_URL, JWT_SECRET, GOOGLE_CLIENT_ID)
   - npm run dev
3. For mobile (Expo):
   - cd mobile-app
   - npm install
   - expo start

Roadmap / how you can contribute
- Project setup and authentication
- Workout logging and exercise library
- History and progress charts
- Reminders and calendar integration
- Testing and deployment

Contact / owner
- Repository owner: harinigunasekaran26
