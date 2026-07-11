# AI Notes App

A modern Next.js application for capturing notes, generating short summaries, and organizing them with tags.

## Features
- Create and save notes quickly
- Generate simple summaries from note content
- Organize notes with automatic tags
- Clean, modern UI built with Next.js and Tailwind-style CSS

## Tech Stack
- Next.js
- React
- TypeScript
- Node.js

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm run dev
   ```

3. Open your browser at:
   ```text
   http://localhost:3000
   ```

## Project Structure
- `app/page.tsx` — main note-taking UI
- `app/api/notes/route.ts` — backend route for note summarization and tagging
- `app/globals.css` — global styling

## Build
To create a production build:
```bash
npm run build
```
