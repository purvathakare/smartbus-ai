# SmartBus AI — Vercel Edition

Vercel-native React/Vite demonstration of a Smart School Bus Tracking System using an agentic workflow.

## Local UI
```bash
npm install
npm run dev
```

## Full local app including API functions
```bash
npx vercel dev
```

## Deploy
1. Push this folder to a new GitHub repository.
2. Import the repository in Vercel.
3. Framework: Vite; Build: `npm run build`; Output: `dist`; Install: `npm install`.
4. Deploy.

API endpoints: `/api/health`, `/api/dashboard`, `/api/simulate?event=traffic`.

No API key is required for this presentation demo. Never commit secret keys to GitHub.
