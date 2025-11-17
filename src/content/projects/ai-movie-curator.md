---
title: "AI Movie Curator"
description: "AI-powered movie recommendation system using Google Gemini API, Firebase Auth, semantic ranking and OMDb metadata filtering."
tech: ["react", "firebase", "gemini-api", "omdb", "recharts"]
features: ["Google Gemini semantic ranking", "Firebase authentication", "OMDb metadata integration", "User watchlists", "Watch history analytics"]
github: "https://github.com/pri2003yam"
live: "https://ai-movie-curator.vercel.app"
stars: 0
order: 2
---

## Overview

AI Movie Curator is an intelligent recommendation interface that combines the Google Gemini API with OMDb metadata and user preferences to deliver personalized, curated movie lists.

## Key Features

- Semantic ranking using language-model embeddings (Google Gemini) to match user intent with movie descriptions.
- Secure user authentication using Firebase Auth and user-specific watchlists.
- OMDb integration for rich metadata (ratings, posters, release info).
- Lightweight analytics and charts (Recharts) to visualize watch history and trends.

## Architecture & Tech

- Frontend: React
- Backend: Serverless endpoints / Firebase functions
- AI: Google Gemini API
- Data: Firestore / OMDb API

## Run locally

```bash
git clone https://github.com/pri2003yam/ai-movie-curator.git
cd ai-movie-curator
npm install
# provide FIREBASE_CONFIG and GEMINI_API_KEY in .env
npm run dev
```

## Links

- Live: https://ai-movie-curator.vercel.app
- Repo: https://github.com/pri2003yam

