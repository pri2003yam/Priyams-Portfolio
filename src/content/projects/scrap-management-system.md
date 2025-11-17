---
title: "Scrap Management System"
description: "Full-stack scrap collection platform with real-time chat (Socket.io), dealer dashboards, workflow automation, and optimized MongoDB queries."
tech: ["react", "nodejs", "mongodb", "jwt", "recharts", "socket.io", "express"]
features: ["Real-time chat with Socket.io", "Dealer dashboards with analytics", "Workflow automation", "JWT authentication", "MongoDB aggregation pipelines"]
github: "https://github.com/GeneBuster/let-scrap"
live: "https://let-scrap-5z4c.vercel.app"
stars: 0
order: 1
---

## Overview

A production-oriented full-stack platform to manage scrap collection and dealer workflows. The app focuses on real-time collaboration (chat and live status), streamlined pickup scheduling, and powerful dashboards for dealers and admins.

## Key Features

- Real-time chat and notifications with Socket.io for instant coordination between collectors and dealers.
- Dealer dashboards with visual analytics (Recharts) to track collections, revenue and performance.
- Workflow automation: dynamic status updates, auto-assignment of pickups, and retry logic for failed jobs.
- Optimized MongoDB queries and aggregation pipelines for fast reporting on large datasets.
- Secure authentication using JWT and role-based access control.

## Architecture & Tech

- Frontend: React
- Backend: Node.js + Express
- Realtime: Socket.io
- Database: MongoDB

## Run locally

```bash
git clone https://github.com/pri2003yam/your-scrap-repo.git
cd your-scrap-repo
npm install
# create .env with MONGO_URI and JWT_SECRET
npm run dev
```

## Links

- Live: https://let-scrap-5z4c.vercel.app
- Repo: https://github.com/pri2003yam

