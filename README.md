# Clearday

A personal daily operating system built for Sara — open it in the morning and the whole day is already laid out, so the mental load lives in the app instead of in your head.

## What's inside

- **Today** — a timestamped, checkable timeline of the whole day. It knows the difference between pickup days (free until 11:30) and no-pickup days (free until 12:30) via a one-tap toggle, and adjusts the work block and bonus block automatically. Includes AM/PM skincare steps, supplement check-offs, rotating focus blocks (Amazon influencer, AI side hustle, decluttering, digital cleanup, budget & vacation planning), daily core exercises, Sophia's afternoon planned in 30-minute activity blocks, and rotating evenings (date night, game night, coloring/hobby night, weekly planning).
- **Journal** — morning prompts: one affirmation, one manifestation, three gratitudes, a win from yesterday, and today's intention — plus a brain-clear box, meditation/affirmation links, streak tracking, and browsable past entries.
- **Gym** — log exercises as weight × reps sets, see what you lifted last time (one-tap copy), per-exercise progress table and trend line, and a post-workout symptom/soreness log.
- **Meals** — a visual recipe box (cards with photos stored on-device), links out to recipe websites, a weekly dinner planner whose picks show automatically in the Today dinner block, and a prep & shopping checklist.
- **Sophia** — an activity idea bank tagged by skill area (fine motor, gross motor, language, sensory, creative, cognitive, imaginative, practical life) that feeds the afternoon plan. Add your own ideas anytime.
- **More** — brain dump (with "put on today's list"), plus editors for everything: schedule blocks and times, weekday rotations, supplements, skincare steps, and links. Every block has a "What's inside" content type (meditation links, journal prompts, skincare steps, supplements, gym log, Sophia plan, dinner plan, rotating notes, or a plain check-off), and supplements, skincare steps, and links each carry their own days of the week — so any day can be built block by block, entirely different from the next. Export/import a JSON backup.

## How to use it

`index.html` is the entire app — no build, no server, no account.

- Open the file in any browser, or host it anywhere static (GitHub Pages works: Settings → Pages → deploy from branch).
- On your phone, use **Add to Home Screen** so it opens like an app.
- All data is stored privately in the browser's localStorage. Use **More → Export backup** to move devices or keep a safety copy.

## Customizing

Everything visible is editable in the app itself (More tab). Defaults — the schedule template, rotations, activity bank, skincare steps, supplements — live at the top of the `<script>` in `index.html` in the `defaults()` function if you ever want to change what a fresh install starts with.
