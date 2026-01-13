---
title: IA Profesor · Fullstack Education Platform
publishDate: 2024-07-20 00:00:00
img: /assets/stock-2-new.jpg
img_alt: Education dashboard with learning paths, progress analytics, and AI tutor chat
description: |
  Fullstack learning platform featuring an AI tutor with streaming responses, learning paths, achievements, and analytics, built with Next.js and NestJS.
tags:
  - Next.js
  - NestJS
  - Fullstack
projectUrl: https://ia-profesor.vercel.app
---

# IA Profesor · Fullstack Education Platform

IA Profesor is a fullstack learning platform that combines an AI tutor with structured learning paths, progress tracking, and rewards. The experience is designed for students and educators, with a responsive web interface and a REST API that powers sessions, analytics, and personalised learning history.

## 🧭 Product Scope

- AI tutor with streaming responses and session history.
- Learning paths, achievements, and engagement analytics.
- Dashboard for students to track progress and activity.
- Secure authentication and profile management.

## 🧱 Frontend (Next.js)

The frontend uses Next.js 15 with the App Router and a UI tuned for educational workflows. It includes a modular component library, client helpers, and a dedicated auth provider to manage Supabase sessions.

- **Framework:** Next.js 15 (App Router) + React 19.
- **Styling & Motion:** Tailwind CSS and Framer Motion for responsive layouts and guided interactions.
- **Auth:** Supabase JS for authentication and session handling.
- **Structure:** `app/` routes and layouts, `components/` UI sections, `lib/` clients/helpers, `context/` auth provider, `public/` assets.
- **Scripts:** `npm run dev`, `npm run build`, `npm run start`.
- **Env variables:** `NEXT_PUBLIC_API_BASE_URL`, `NEXT_PUBLIC_SUPABASE_URL`, `NEXT_PUBLIC_SUPABASE_ANON_KEY`, `NEXT_PUBLIC_BASE_URL`.
- **Deploy:** Vercel with `npm run build` and `NEXT_PUBLIC_*` variables configured.

## 🛠️ Backend (NestJS)

The backend exposes a REST API built on NestJS 11 with Supabase auth, Prisma ORM, and clear validation pipelines. It powers tutor sessions, user state, rewards, and analytics.

- **Framework:** NestJS 11 with REST controllers.
- **Data:** Prisma ORM with PostgreSQL on Supabase.
- **Auth:** Supabase Auth + JWT.
- **Docs:** Swagger available at `GET /api`.
- **Validation:** Class Validator + Transformer.
- **Structure:** `src/` codebase, `prisma/` schema and migrations, `dist/` production build, `test/` tests.
- **Scripts:** `npm run build`, `npm run start`, `npm run start:dev`.
- **Env variables:** `DATABASE_URL`, `SUPABASE_URL`, `SUPABASE_SERVICE_ROLE_KEY`, `JWT_SECRET`, `CORS_ORIGINS`, `PORT`.
- **Key endpoints:** `GET /users/me`, `GET /tutor/sessions`.
- **Deploy:** Railway with `npm run build` and `npm run start`, CORS configured for the frontend domain.

## ✅ Outcomes

- Centralised fullstack architecture aligned to learning and tutoring workflows.
- AI tutor integrated with session persistence and progress history.
- Clear deployment strategy for both web and API layers.
