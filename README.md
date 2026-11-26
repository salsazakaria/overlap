# Overlap

Find the hours your remote team actually shares.

**Try it live → [overlap-io.netlify.app](https://overlap-io.netlify.app/)**

Pick your cities, set everyone's working hours, and Overlap shows where the days meet, with the best window in everyone's local time. Drag a bar to shift someone's hours and watch the shared time grow. Copy the link to share the exact setup.

## How to use

1. **Add your cities.** Overlap starts with two cities. Tap a city's name or circle to swap it for another, or press **+ Add city** to add more (up to 5). Type to search, then pick one from the list.
2. **Set working hours.** Under each city, choose a start and end time from the two time pills. Hours that run past midnight (like 16:00 → 01:00) work too.
3. **Drag to adjust.** Grab any coloured bar and slide it left or right to shift that person's hours in 30-minute steps. The shared time updates as you drag, with a little confetti when it grows.
4. **Read the result.** The big headline shows how many hours everyone overlaps. The dashed band and the black **Together** bar show where, and **Best window** lists that slot in each city's local time.
5. **Compare any moment.** Hover over the board (or tap it on mobile) to see what time it is in every city at that point. The coral line marks right now.
6. **Pick your clock.** Switch between **24h** and **12h** at the top.
7. **Share it.** Press **Copy link** and send it. Anyone who opens it sees the same cities and hours.

Your last setup is remembered in your browser, so it's there when you come back.

## Features

- 24-hour board for up to 5 cities, with a "now" marker
- Drag bars or use the time pickers to adjust working hours
- Best meeting window shown in every city's local time
- Hover (or tap on mobile) to compare times at any point in the day
- 12h / 24h toggle, light and dark mode
- Shareable links: state lives in the URL (`?with=jakarta~960~60_san-francisco~480~1020`)
- Uses today's UTC offsets, so daylight saving is handled

## Run it

It's a single static file with no build step. Open `index.html` in a browser, or deploy the folder to any static host (Netlify, Vercel, GitHub Pages).

---

by Salsa · [LinkedIn](https://www.linkedin.com/in/salsazakaria/) · [X](https://x.com/salsa_creates)
