# 🔴 Muladhara Voice Guide — Full Stack App

Hands-free, fully voiced 60-minute guided sessions for morning and evening Muladhara practice.

## Features
- **Voice-guided** — Web Speech API reads every instruction aloud, hands-free
- **Real asana photos** — sourced from Wikimedia Commons (CC licensed) with credit
- **Live breath visualizers** — animated orbs for Nadi Shodhana and Chandra Bheda
- **Hold timers** — circular countdown rings for every timed pose
- **LAM / So'Ham meditation timers** — 15-min morning, 20-min evening
- **Full day schedule** — every minute from 5 AM to 10:30 PM
- **Wake lock** — screen stays on during sessions
- **iOS/Android ready** — touch-optimized, full-screen PWA compatible
- **Speed control** — 0.8× to 1.2× voice rate

## Hosting

### Option 1: Local
```bash
npm install
npm start
# Open http://localhost:3000
```

### Option 2: Railway (free tier)
1. Push repo to GitHub
2. Go to railway.app → New Project → Deploy from GitHub
3. Set PORT env var (Railway does this automatically)

### Option 3: Render (free tier)
1. Push to GitHub
2. render.com → New Web Service → connect repo
3. Build: `npm install` · Start: `node server.js`

### Option 4: Vercel/Netlify (static)
Drop the `public/index.html` directly — no server needed, runs as pure HTML.

### Option 5: Replit
Import repo, click Run. Share the live URL.

## Sessions
| Session | Steps | Duration |
|---------|-------|----------|
| Morning | 13 steps | ~60–75 min |
| Evening | 9 steps | ~60 min |
| Day Schedule | 24 items | Full day |

## Voice Notes
- Uses browser Web Speech API (built-in, no API key needed)
- Best voices: Chrome on desktop (Daniel/Samantha), Safari on iOS (Siri voices)
- Speed adjustable: 0.8× (slow + clear) recommended for beginners

## Image Credits
All asana images from Wikimedia Commons under Creative Commons license:
- Nina Mel collection — CC BY-SA 3.0
- Kenngott — CC BY-SA 3.0
