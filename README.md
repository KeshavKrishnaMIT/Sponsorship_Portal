# Sponsorship Portal

A role-based sponsorship management portal built to streamline task assignment, committee coordination, and workflow management for event organizing committees.

**Live Demo:** https://sponsorship-portal-sable.vercel.app

---

## Overview

The Sponsorship Portal is a web application that enables Committee Coordinators (CCs) and Organizing Committee (OC) members to manage sponsorship-related activities efficiently.

CCs can create, assign, update, and monitor tasks, while OC members can view and complete tasks assigned to them. The application uses Firebase Authentication for secure login and Cloud Firestore for real-time data storage.

---

## Features

- Secure authentication using Firebase Authentication
- Role-based access control (CC and OC)
- Task creation and assignment
- Task status tracking
- Committee-wise member management
- Timetable support
- Real-time Firestore database integration
- Responsive interface
- Deployed on Vercel

---

## Tech Stack

- Next.js
- React
- TypeScript
- Firebase Authentication
- Cloud Firestore
- CSS
- Vercel

---

## Live Website

https://sponsorship-portal-sable.vercel.app

---

## Installation

Clone the repository:

```bash
git clone https://github.com/KeshavKrishnaMIT/Sponsorship_Portal.git
```

Install dependencies:

```bash
npm install
```

Create a `.env.local` file in the project root:

```env
NEXT_PUBLIC_FIREBASE_API_KEY=YOUR_API_KEY
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=YOUR_AUTH_DOMAIN
NEXT_PUBLIC_FIREBASE_PROJECT_ID=YOUR_PROJECT_ID
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=YOUR_STORAGE_BUCKET
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=YOUR_MESSAGING_SENDER_ID
NEXT_PUBLIC_FIREBASE_APP_ID=YOUR_APP_ID
```

Run the development server:

```bash
npm run dev
```

Open:

```
http://localhost:3000
```

---

## Firebase

Services used:

- Firebase Authentication
- Cloud Firestore

Collections:

- users
- tasks

---

## User Roles

### Committee Coordinator (CC)

- Create tasks
- Assign tasks
- Update any task
- Delete tasks
- Monitor committee progress

### Organizing Committee (OC)

- View assigned tasks
- Update assigned tasks
- Mark tasks as completed

---

## Project Structure

```
src/
├── app/
├── components/
├── data/
├── lib/

public/
styles/
```

---

## Repository

https://github.com/KeshavKrishnaMIT/Sponsorship_Portal

---

## Author

Keshav Krishna Singh

GitHub: https://github.com/KeshavKrishnaMIT
