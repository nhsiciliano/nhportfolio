---
title: Serum Box
publishDate: 2024-06-01 00:00:00
img: /assets/stock-1.jpg
img_alt: Digital control panel managing racks, tubes, and reagents for a laboratory
description: |
  SaaS platform that digitises rack, tube, and reagent traceability for clinical labs, complete with multi-channel billing flows and automated support playbooks.
tags:
  - SaaS
  - Product Development
  - Next.js
---

## Project Overview

Serum Box is a full-stack platform built with **Next.js 14** that centralises inventory, rack, and tube management for clinical labs and research teams. It bundles subscriptions, multi-gateway billing (Stripe, PayPal, MercadoPago), and automated alerts to sustain the day-to-day operations of each lab.

## Role & Responsibilities

- Designed the end-to-end SaaS architecture (domain modelling, Prisma schemas, NextAuth, multitenancy).
- Shipped dashboards, interactive tables, and motion patterns with Chakra UI + Tailwind + Framer Motion.
- Automated onboarding, verification, and support flows with Nodemailer and billing webhooks.
- Ran subscription plan scripts (`testPlans.ts`) to guarantee consistency across upgrades and downgrades.

## Key Challenges

- Modelling rack/tube inventory with auditable, traceable metadata in MongoDB.
- Building granular permission management for secondary lab users without compromising UX.
- Unifying multiple payment gateways into a single billing flow with synced entitlement states.

## Outcomes

- Real-time inventory with proactive stock and expiry alerts.
- Detailed audit logs ready for regulatory compliance checks.
- Frictionless customer activation through automated onboarding and billing orchestration.

## Stack

- **Frontend:** Next.js 14 (App Router, RSC), TypeScript, Chakra UI, Tailwind, Framer Motion, Zustand.
- **Backend:** Next.js server actions, API Route Handlers, NextAuth with Prisma and MongoDB.
- **DevOps:** Prisma Migrate, utility scripts, deployment-ready for Vercel / Node 18.
- **Billing & Comms:** Stripe Billing, PayPal Subscriptions, MercadoPago, Nodemailer, validated webhooks.
