# Paper Tune — PWA

Compound archery paper tuning assistant. Mobile-first PWA with AI tear analysis.

## Deploy to Vercel (5 minutes, free)

1. Go to https://vercel.com and sign up (free)
2. Install Vercel CLI: `npm i -g vercel`
3. From this folder, run: `vercel`
4. Follow the prompts — accept all defaults
5. Done. Your app is live at a URL like `papertune-xxx.vercel.app`

## Or deploy via Vercel web UI (no CLI needed)

1. Go to https://vercel.com/new
2. Choose "Browse" and upload this entire folder as a zip
3. Deploy

## Add to Android home screen

1. Open the app URL in Chrome on your Android phone
2. Tap the three-dot menu → "Add to Home Screen"
3. Or Chrome will show an install banner automatically
4. The app installs and runs full-screen like a native app

## Notes

- Data is stored locally on the device (localStorage)
- Internet required for AI analysis (Anthropic API)
- App shell works offline once cached
- No login required, no server, no database
