# TürkçeGo

A1 Turkish learning web app with Swedish and English explanation languages.

## Run

Install Node.js 20+ then:

```bash
npm install
npm run dev
```

Open the local URL printed by Vite (usually http://localhost:5173).

## Build

```bash
npm run build
```

Deploy the generated `dist` directory to a static hosting service.

## Features
- Swedish / English explanation language selector
- Five interactive A1 lessons, five words each
- Turkish pronunciation through browser Speech Synthesis (depends on device Turkish voice availability)
- Multiple-choice quizzes
- Local progress saving
- Responsive layout

## Limitations
- No login, backend or payment processing yet.
- Progress is per browser/device, not synced.
- Browser speech synthesis requires Turkish voice support.
