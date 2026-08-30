# Second Brain 2.0

A clean rebuild of the original Second-Brain app. The original repository is not used as the runtime codebase.

## What is included
- Habit OS with calendar, daily task tracking, streaks, stars and reward shop
- Performance analytics
- Habit Tracker Coach using Gemini 3.7 Flash
- Second Brain dashboard
- Revision queue with 1/3/7/14/21/28/30 day cycles
- Wisdom folders + Oracle
- Brain Dump + AI categorization
- Urge Interceptor
- Data backup/export
- Themes
- Local persistence plus optional Firebase sync

## Run
```bash
npm install
npm start
```

## Gemini
Open **Command Center → Gemini API key** and paste your Gemini API key for the test build. The AI calls target `gemini-3.7-flash`.

For a production deployment, move the Gemini request behind a server/API route so the key is never exposed to the browser.

## Preview
This repo includes a Codespaces dev container configured to start the app on port 3000 and open the forwarded port as a preview.