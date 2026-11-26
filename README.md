# Overlap

Find the hours your remote team actually shares.

**Try it live → [overlap-io.netlify.app](https://overlap-io.netlify.app/)**

<p align="center">
  <a href="media/overlap-launch.mp4"><img src="media/overlap-launch.gif" width="360" alt="Overlap demo: add people, share the link, drag bars until everyone overlaps"></a>
  <br>
  <sub><a href="media/overlap-launch.mp4">▶ Watch the full launch video</a></sub>
</p>

Add the people you want to meet, set everyone's working hours, and Overlap shows where the days meet, with the best window in everyone's local time. Drag a bar to shift someone's hours and watch the shared time grow. Copy the link to share the exact setup.

## How to use

1. **Add yourself.** Type your name in the first row and tap the city to pick yours (54 cities to choose from).
2. **Set your hours.** Choose a start and end time with the two time pills. Hours that run past midnight, like 16:00 → 01:00, work too.
3. **Add more people.** Press **+ Add person**, pick their city, and type their name. Up to 5 people, and several can share a city.
4. **Find the overlap.** The headline shows how many hours everyone shares. The dashed band and the black **Together** bar show where, and **Best window** lists that slot in each person's local time.
5. **Adjust by dragging.** Slide any coloured bar left or right to shift someone's hours in 30-minute steps, and watch the shared time grow.
6. **Compare any moment.** Hover over the board (or tap it on mobile) to see what time it is for everyone at that point. The coral line marks right now.
7. **Switch clocks.** Toggle between **24h** and **12h** at the top.

Your last setup is saved in your browser, so it's still there when you come back.

### Plan with friends

The whole setup lives in the link, so you can pass it around:

1. Add your name, city and hours, then press **Copy link**.
2. Send the link to a friend. They open it, press **+ Add person**, add their name, city and hours, then copy the link again.
3. They send it to the next friend, or back to you. Pass it one person at a time, so everyone adds themselves to the newest link.
4. Once everyone's in, share the final link so the whole group sees the same overlap and best window. Works best for small groups of up to 5.

Tip: the board's time axis follows the first person's time zone, but the **Best window** chips and the hover/tap times always show each person's own local time.

## Features

- 24-hour board for up to 5 people, each with a name and city, plus a "now" marker
- Drag bars or use the time pickers to adjust working hours
- Best meeting window shown in every person's local time
- Hover (or tap on mobile) to compare times at any point in the day
- 12h / 24h toggle, light and dark mode
- Shareable links: state lives in the URL (`?with=jakarta~960~60~Salsa_san-francisco~480~1020~Dina`)
- Uses today's UTC offsets, so daylight saving is handled

## Run it

It's a single static file with no build step. Open `index.html` in a browser, or deploy the folder to any static host (Netlify, Vercel, GitHub Pages).

---

by Salsa · [LinkedIn](https://www.linkedin.com/in/salsazakaria/) · [X](https://x.com/salsa_creates)
