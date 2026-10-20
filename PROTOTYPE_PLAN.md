# Prototype Plan — Self-Improvement App

## Vision
A mobile-first web app that pairs **online fitness coaching** with broader self-improvement: habits, mindset, nutrition basics, and accountability — so users improve body and routines in one place.

## Problem
People start fitness and self-improvement alone, lose momentum, and bounce between apps (workouts, habits, coaching). They need guided plans, human (or hybrid) coaching, and simple progress they can see weekly.

## Target users (v0)
- Busy adults (25–45) who want structured workouts + habit support
- Beginners to intermediate; not competitive athletes
- Willing to pay a modest monthly fee for coaching + plan

## Core value proposition
“Your coach + your plan + your habits — in one weekly loop.”

## Prototype scope (build this first)

### In scope (MVP prototype)
1. **Auth & profile** — sign up, basic profile (goals, experience, schedule)
2. **Fitness coaching surface**
   - Weekly workout plan view (pre-built templates by goal)
   - Session logging (completed / skipped + notes)
   - Simple messaging or check-in with a “coach” (can be mock/admin for prototype)
3. **Self-improvement add-ons**
   - Habit tracker (3–5 habits max)
   - Weekly reflection (short form: energy, mood, wins)
   - Micro-lessons / tips (static content: mindset, recovery, nutrition basics)
4. **Progress dashboard**
   - Streaks, sessions completed this week, habit completion %
5. **Admin / coach lite**
   - Assign a plan template to a user
   - View user check-ins (enough to demo coaching)

### Out of scope (later)
- Live video sessions, wearables, custom AI program generation, social feed, meal planning, payments at scale, native apps

## User journeys to demo
1. New user → set goal → get week-1 plan → complete a workout → log habit → submit weekly check-in
2. Coach/admin → open user → see progress → leave short feedback / assign next week’s template

## Suggested feature modules
| Module | Prototype behavior |
|--------|--------------------|
| Onboarding | Goals, days available, experience level |
| Plans | 2–3 static templates (fat loss, strength, consistency) |
| Workouts | Exercise list + sets/reps; mark done |
| Habits | e.g. sleep, steps, water, reading |
| Coaching | Async notes + weekly check-in thread |
| Content | 5–10 tip cards |
| Progress | Week summary chart / counts |

## Success criteria for the prototype
- A stranger can complete journey #1 in <10 minutes without help
- Coach journey #2 works with fake data for 2–3 demo users
- Feels like one product, not three glued widgets
- Clear “what’s next this week” on the home screen

## Tech direction (flexible)
- Web app (React/Next or similar) + simple backend/API + DB
- Auth (email or magic link)
- Seed data for plans, tips, and demo coach users
- Deploy a public demo URL for feedback

## Prototype timeline (example 2–3 weeks)
| Phase | Focus |
|-------|--------|
| Week 1 | Auth, profile, plan templates, workout logging |
| Week 2 | Habits, weekly check-in, progress home |
| Week 3 | Coach view, polish, demo script + seed data |

## Risks & assumptions
- Coaching quality matters more than UI polish — mock coach feedback carefully for demos
- Don’t overbuild content; reuse templates
- Habit + fitness in one app only works if home screen stays simple

## Next after prototype
- Real coach workflows, payments, personalized plans, notifications, mobile polish
