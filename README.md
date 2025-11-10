# Montage S F M — Render Ready
Deploy on Render (Web Service)

## Build Command
```
npm install && npm --prefix client install && npm --prefix client run build && npm --prefix server install
```

## Start Command
```
node server/index.js
```

Environment variables (optional):
- OPENAI_API_KEY
- ELEVENLABS_API_KEY

The Express server serves built React from `client/dist` and handles `/api/*` and `/health`.
