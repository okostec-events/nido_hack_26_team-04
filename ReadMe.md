# MatchUp — Student-Employer Opportunity Platform

A platform connecting high school students with internships, competitions, hackathons, and opportunities using AI-powered matching.

## Features
- Student profiles with CV, grades, skills, and achievements
- Opportunity catalog for internships and competitions
- AI-assisted matching with fallback rule-based scoring
- Responsive web interface

## Setup & Run

### Prerequisites
- Node.js (v16 or higher) — download from [nodejs.org](https://nodejs.org)

### Quick Start
1. Clone this repo: `git clone https://github.com/okostec-events/nido_hack_26_team-04.git`
2. Enter the folder: `cd nido_hack_26_team-04-main`
3. Install dependencies: `npm install`
4. Start the server: `npm start`
5. Open your browser to **http://localhost:3001**

### For Teams
- One person edits one file at a time to avoid conflicts
- Commit and push changes often
- Use GitHub Desktop for easy version control

### Optional: Enable AI Matching
Set your OpenAI API key for smarter match recommendations:
```bash
export OPENAI_API_KEY=your-key-here
npm start
```
Without it, the platform uses local rule-based scoring.

## Project Structure
- `server.js` — Express backend with API endpoints
- `index.html` — Frontend UI and client logic
- `data/db.json` — Sample data (students and opportunities)
- `package.json` — Dependencies and scripts

## API Endpoints
- `GET /api/students` — List student profiles
- `POST /api/students` — Save/update student profile
- `GET /api/opportunities` — List opportunities
- `POST /api/opportunities` — Save/update opportunity
- `POST /api/match` — Compute match between student and opportunity
- `POST /api/match-all` — Get all matches for a student

## Development
- Edit `index.html` for UI changes
- Edit `server.js` for backend logic
- Data persists in `data/db.json`
- Refresh browser to see changes

Your live URL will be set up by your mentor before the event. Once GitHub Pages is enabled on your repo, the pattern is **https://okostec-events.github.io/nido_hack_26_team-04/**

---

## Step 5 — Submit

Before the deadline, fill in **SUBMISSION.md** and push it to your repo. That's what the judges will read.

---

**Questions?** Ask any of the mentors — we're here to help.
