<p align="center">
  <img src="readme-banner.svg" width="100%" alt="Supun Feedback Management System" />
</p>

<p align="center"><b>A QR-based guest feedback system built for hospitality environments.</b></p>

<p align="center">
  <img src="https://img.shields.io/badge/React-Web-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Firebase-Backend-FFCA28?style=flat-square&logo=firebase&logoColor=111827" alt="Firebase" />
  <img src="https://img.shields.io/badge/Capacitor-Mobile-119EFF?style=flat-square&logo=capacitor&logoColor=white" alt="Capacitor" />
</p>

---

## Project Snapshot

| | |
|---|---|
| **Business problem** | Guest feedback is often slow, scattered and hard to track by location. |
| **Solution** | A QR-driven feedback flow with secure admin management and notifications. |
| **Users** | Guests + administrators. |
| **Platforms** | Web, Android and iOS through Capacitor. |

## Experience Context

<div align="center">
  <img src="public/rest1.jpeg" width="72%" alt="Hospitality environment" />
</div>

## Key Features

- QR-based access by location code
- Multi-step validated guest feedback form
- Zone and location-aware submissions
- Secure Firebase Authentication
- Protected management area
- Firestore security rules
- Email notifications for feedback updates
- Responsive mobile-first interface
- Android and iOS packaging with Capacitor

## User Flow

`Scan QR` → `Open location` → `Submit feedback` → `Private confirmation` → `Admin reviews` → `Status update`

## What This Project Demonstrates

- Converting a service problem into a simple guest-facing workflow
- Capturing structured feedback by location and zone
- Protecting management data while keeping public submission easy
- Supporting web and mobile delivery from one React codebase
- Connecting customer experience data to operational follow-up

## Security & Data Design

- Public users cannot read stored feedback
- Public submissions are validated by Firestore rules
- Admin routes require authentication
- Email credentials are stored as deployment secrets
- Server timestamps are used for important records

## Repository Context

This repository is a **forked/collaborative codebase**. For interview discussion, individual work should be explained using the repository's commit and collaboration history rather than treating the full codebase as single-author work.

## Run Locally

```bash
npm install
npm run dev
```

Copy `.env.example` to `.env` and add the Firebase web configuration.

Build:

```bash
npm run build
```

Mobile helpers:

```bash
npm run mobile:android
npm run mobile:ios
```

---

<p align="center"><b>Fast guest input → structured data → clearer service decisions.</b></p>
