# TriageAI

Live voting experience for AI task triage. Participants swipe or tap to classify tasks as:

- **Automatizable** (AI does it, I review)
- **Augmented** (We co-pilot together)
- **Human** (This can't be delegated)

## Features

- Real-time multiplayer voting via Supabase
- Swipe-to-vote with haptic feedback
- QR code for easy session joining
- Live results visualization
- Facilitator control panel
- Export results to CSV

## Quick Start

1. Visit the deployed URL
2. Create a session or join with a code
3. Start voting!

## Local Development

```bash
# Serve locally
npx serve .
```

## Deployment

This project is configured for Vercel deployment:

```bash
vercel
```

## Tech Stack

- React 18 (via CDN)
- Supabase (real-time database)
- Vanilla CSS with animations

## License

MIT
