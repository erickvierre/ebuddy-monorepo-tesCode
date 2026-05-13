# EBUDDY Fullstack Monorepo

Basic fullstack monorepo project built using Express.js, Next.js, Firebase, TypeScript, and Turborepo.

---

# Technologies

## Frontend
- Next.js
- React
- Material UI (MUI)
- Redux Toolkit

## Backend
- Express.js
- Firebase Admin SDK
- Firestore

## Monorepo
- Turborepo

---

# Project Structure

```bash
ebuddy-monorepo/
├── apps/
│   ├── backend-repo/
│   └── frontend-repo/
│
├── packages/
│   └── shared-types/
│
└── README.md
```

---

# Features

- Fullstack architecture
- Express REST API
- Firebase Firestore integration
- Fetch and update user API
- Authentication middleware
- Shared TypeScript interfaces
- Material UI frontend
- Basic monorepo structure

---

# Installation

## Clone Repository

```bash
git clone YOUR_GITHUB_REPOSITORY
```

Enter project folder:

```bash
cd ebuddy-monorepo
```

---

# Install Dependencies

## Backend

```bash
cd apps/backend-repo
npm install
```

## Frontend

```bash
cd ../frontend-repo
npm install
```

---

# Running Backend

Open terminal:

```bash
cd apps/backend-repo
npm run dev
```

Backend server:

```txt
http://localhost:5000
```

---

# Running Frontend

Open another terminal:

```bash
cd apps/frontend-repo
npm run dev
```

Frontend server:

```txt
http://localhost:3000
```

---

# API Endpoints

## Fetch User Data

```http
GET /fetch-user-data
```

Authorization header:

```txt
Authorization: token
```

---

## Update User Data

```http
POST /update-user-data
```

Request body example:

```json
{
  "uid": "1",
  "name": "Erick",
  "age": 24
}
```

Authorization header:

```txt
Authorization: token
```

---

# Firebase Setup

Create Firebase project:

https://console.firebase.google.com/

Enable:
- Firestore Database

Then configure Firebase credentials.

---

# Frontend Preview

```txt
EBUDDY FULLSTACK TEST

[ Fetch User Data ]
```

---

# Shared Types

Located in:

```bash
packages/shared-types
```

Example:

```ts
export interface User {
  uid: string
  name: string
  age: number
}
```

---

# Technical Stack

| Layer | Technology |
|---|---|
| Frontend | Next.js |
| Backend | Express.js |
| Database | Firebase Firestore |
| UI | Material UI |
| Language | TypeScript |
| Monorepo | Turborepo |

---

# Notes

This project was built from EBUDDY Fullstack Technical Test.
