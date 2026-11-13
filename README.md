# Sleep Shift Planner

A single-page app that plans your bedtime and wake time for the days around your flights.

- Enter your usual wake time, how much sleep you need, and your home time zone.
- Add each flight: type the flight number and date and press **Look up** to fill in the times and time zones, or enter them by hand. Then set how long before departure you need to be up.
- The plan moves your sleep earlier in small daily steps before early departures, protects as much sleep as it can on travel days (including overnight flights), and eases you back to your usual times afterwards.
- Each day lists light, nap and caffeine guidance based on sleep-regularity advice (e.g. Matthew Walker's *Why We Sleep*) and circadian research.

Open `index.html` in any browser. Your inputs are saved in your browser only.

## Flight-number lookup

- **Opened as a file / your own site:** lookups use [AeroDataBox](https://rapidapi.com/aedbx-aedbx/api/aerodatabox) live schedules. Get a free RapidAPI key, then paste it under *How the plan adjusts → Flight lookup key*. The key is stored only in your browser.
- **Opened as a Claude artifact:** the page can't reach outside websites, so it asks Claude for the flight's usual published schedule. These are estimates labelled with a confidence level; check them against your booking.

This is general guidance, not medical advice.
