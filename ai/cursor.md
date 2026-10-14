# Text-Project — Cursor notes

This file is project guidance for Cursor. Keep it short and update it as the project grows.

## Project

- Name: Text-Project
- Owner: Rafiqul
- Status: early / starting from an empty workspace

## How to work here

- Work directly in code: create, debug, and iterate.
- Only change files that are needed for the current task.
- Do not create git commits unless Rafiqul asks for a commit.
- Do not push unless Rafiqul asks to push.

## Communication

- Rafiqul often writes in Bangla or Banglish.
- Reply in the same language they used, unless they ask otherwise.
- Lead with the answer, then give short supporting detail.

## Tech stack

- Runtime: Node.js
- Language: TypeScript (strict; avoid plain `.js` / `.jsx` except when a tool requires it)
- Framework: Next.js (App Router)
- UI: React with TypeScript (`.tsx`)
- Package manager: npm (until we decide otherwise)

## Conventions

- Prefer TypeScript types and interfaces over `any`.
- Keep app code in the Next.js App Router (`app/`).
- Use Server Components by default; add `"use client"` only when the file needs browser APIs, state, or event handlers.
- Put shared UI in `components/`, shared logic in `lib/`.
- How to run locally: `npm install` then `npm run dev`
- How to test: add tests when the app exists; run with `npm test`

## Current focus

- Define the product (what this text project should do).
- Scaffold the Next.js + TypeScript app.
- Keep this file in sync when stack choices change.
