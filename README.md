# Good Deeds Done Dirt Cheap

A small, cosy web app for logging one good deed a day and growing a streak through the year.

## Features

- One deed per day, locked once saved
- Missed days can be filled in once, then they lock too
- Current streak, longest streak and total deeds for the year
- Streak milestone badges at 7, 30, 60, 100, 150, 200, 250, 300 and 365 days
- Year view with 12 month calendars
- Can be added to your phone's home screen

## Where data is saved

- **On GitHub Pages:** deeds are saved in the browser on each device (localStorage). They do not sync between devices. Clearing your browser data erases them.
- **On the Claude artifact version:** deeds are saved to your Claude account and sync between devices.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole app (HTML, CSS and JavaScript in one file) |
| `manifest.json` | Home-screen name, colours and icons |
| `icon-*.png` | App icons |

## Hosting on GitHub Pages

Settings > Pages > Source: **Deploy from a branch**, Branch: `main`, folder `/ (root)`.
