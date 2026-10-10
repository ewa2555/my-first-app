# Angielski Tutor

A web app that helps Polish speakers learn English. The interface is bilingual (Polish + English).

## What it does

1. **Assessment quiz** measures two separate levels: writing, and speaking/understanding.
2. **You choose** which skill to focus on improving.
3. **Practice** covers vocabulary, grammar, and sentence structure. You can answer by typing or by talking, and switch at any time.

Grading is deterministic (rule-based, no AI model), so the same answer always gets the same result.

## Status

Phase 1 (core experience, no accounts) is a single-file prototype in `index.html`.

## Roadmap

- **Phase 1:** quiz, grading, focus choice, practice loop (in progress)
- **Phase 2:** user accounts (email + password) and saved progress
- **Deployment:** hosting on Vercel, database and login on Supabase, installable as a PWA on phones

## Run it locally

Open `index.html` in Chrome. Voice input uses the browser's built-in speech recognition, which works in Chrome.

## Tech

HTML, CSS, and vanilla JavaScript. Planned: Vercel (hosting), Supabase (database and auth).
