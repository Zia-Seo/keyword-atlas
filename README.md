# Keyword Atlas — Free Edition (Powered by Gemini AI)

A research-powered keyword discovery tool. Enter any tool keyword like "Personal Injury Settlement Calculator" and get 25-40 alternative search terms used in different countries — same intent, different words.

**Cost: $0 forever.** Uses Google Gemini's free tier (1,000 requests/day).

## Quick Start

Open `DEPLOYMENT-GUIDE.html` in your browser for the complete step-by-step visual guide.

## Files

- `index.html` — the website frontend
- `api/research.js` — backend that calls Gemini API
- `vercel.json` — Vercel deployment config
- `package.json` — Node.js metadata
- `DEPLOYMENT-GUIDE.html` — visual deployment walkthrough

## Deployment Summary

1. Get free Gemini API key at https://aistudio.google.com/apikey
2. Create GitHub account at https://github.com/signup
3. Upload these files to a new GitHub repo (drag-and-drop in browser)
4. Sign up at https://vercel.com using GitHub
5. Import the repo on Vercel and deploy
6. Add `GEMINI_API_KEY` env var in Vercel settings, redeploy

Total time: 30 minutes. No coding, no terminal commands needed.

## Tech Stack

- Frontend: Pure HTML/CSS/JavaScript
- Backend: Vercel Serverless Function (Node.js)
- AI: Google Gemini 2.0 Flash (free tier)
- Hosting: Vercel (free tier)
- Code storage: GitHub (free)

## Free Tier Limits

| Service | Free Tier | Enough for? |
|---------|-----------|-------------|
| Gemini API | 1,000 requests/day | Yes (any personal use) |
| Vercel | 100GB bandwidth/month | Yes (~50,000 page views) |
| GitHub | Unlimited public repos | Yes |

For most personal use, this is effectively unlimited and stays free forever.
