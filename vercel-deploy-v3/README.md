# Real Estate Study Assistant

AI-powered study companion for real estate exam prep with deep comprehension and ELI5 explanations.

## Features

- 📚 **PDF Upload** - Upload textbooks for AI analysis
- 🧠 **Deep AI Comprehension** - Not just text extraction, actual understanding
- 💡 **ELI5 Mode** - "Explain Like I'm 5" with analogies
- 🎴 **Smart Flashcards** - With spaced repetition (SM-2 algorithm)
- ❓ **Scenario-Based Quizzes** - Real-world questions with teaching explanations
- 📊 **Market Analysis** - AI-powered real estate market insights
- 🏠 **Comps Report** - Property valuation analysis
- 📅 **Study Schedule** - Auto-generated based on exam date
- 📈 **Progress Tracking** - Concept mastery and quiz analytics
- 📱 **PWA Support** - Install on mobile, works offline

## Tech Stack

- React + TypeScript + Vite
- Tailwind CSS (Glassmorphism UI)
- Dexie.js (IndexedDB for local storage)
- PDF.js (PDF text extraction)
- Tavily API (AI search and analysis)

## Quick Start

```bash
# Install dependencies
npm install

# Run dev server
npm run dev

# Build for production
npm run build
```

## Deployment

### Vercel (Recommended)
1. Push to GitHub
2. Connect repo at https://vercel.com
3. Auto-deploys on every push!

## API Key Setup

1. Get a free Tavily API key at https://tavily.com
2. Enter it in the app when prompted
3. Key is stored only in your browser (localStorage)

## Privacy

- All data stays in your browser (IndexedDB)
- API calls go directly from browser to Tavily
- No backend server, no data collection

---

Built with 🌶️ by Bob for Muneeb
