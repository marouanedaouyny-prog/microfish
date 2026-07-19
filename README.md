# MicroFish

AI-powered interview simulator that analyzes your CV against a job description using 5 independent AI interviewer agents.

## Features

- **5 AI Interviewer Personas** — HR, Technical, Manager, CEO, Critical Reviewer
- **CV + JD Analysis** — Upload CV and job description for multi-agent simulation
- **Comprehensive Reports** — Interview questions, weakness analysis, skill gaps, confidence score, improvement plan
- **Arabic Support** — Full localization with `/ar` route
- **Revenue Model** — Free (3 sims), Premium ($5), Professional ($15/mo)

## Tech Stack

TypeScript, Next.js 16, React 19, Tailwind CSS v4

## Getting Started

```bash
cd microfish/web
npm install
npm run dev    # http://localhost:3000
```

## Architecture

Next.js 16 App Router with simulation engine (`src/lib/simulation-engine.ts`), in-memory mock store, and type definitions. Routes: `/dashboard`, `/upload`, `/simulation/[id]`, `/results/[id]`, `/profile`.
