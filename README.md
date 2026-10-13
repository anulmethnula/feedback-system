<div align="center">

# Supun Feedback Management System

**QR-based guest feedback and management platform**

<img src="public/rest1.jpeg" alt="Supun Feedback System" width="720" />

</div>

---

## Overview

A responsive feedback system built for hospitality use. Guests can scan a QR code, submit feedback, and receive a private confirmation while administrators manage responses securely.

## Main Features

- QR-based feedback access
- Multi-step guest feedback form
- Location and zone based feedback
- Secure admin login
- Protected management dashboard
- Firebase Firestore storage
- Email notifications
- Android and iOS support through Capacitor

## Tech Stack

`React` · `Vite` · `Firebase` · `Firestore` · `Capacitor` · `Recharts`

## Run Locally

```bash
npm install
npm run dev
```

Copy `.env.example` to `.env` and add your Firebase configuration.

## Build

```bash
npm run build
```

For Firebase deployment:

```bash
firebase deploy --only functions,firestore:rules,hosting
```

## Mobile

```bash
npm run mobile:android
npm run mobile:ios
```

---

<div align="center">
  <b>Simple feedback • Better insights • Better service</b>
</div>
