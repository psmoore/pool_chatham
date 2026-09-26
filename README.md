# Chatham County Aquatic Center — Pool Relay embed preview

A mockup of the Hours section of [aquatic.chathamcountyga.gov](https://aquatic.chathamcountyga.gov/): both
pools (the 50 m Lap Pool and the Recreation Pool), the center's programs and the swim clubs that publish
times, on live [Pool Relay](https://www.poolrelay.com) calendars, with a page per program.

Not an official Chatham County page. It says so in a ribbon across the top.

Built with `python3 build.py` (the chrome lives there; edit it, not the HTML) and served by GitHub Pages.

## The pages

| Page | Calendar | Scoped to |
|---|---|---|
| `index.html` — Find a swim time | [`8WBzX5Pf…`](https://www.poolrelay.com/v/8WBzX5PfGeJJPSB2chuumL) | one pool at a time, lane by lane; **Pools** menu; **Teams** menu |
| `week.html` | [`AAsteRpn…`](https://www.poolrelay.com/v/AAsteRpnoYZ3rQmcNYADY3) | one pool, the whole week; **Pools** menu, opens on the Lap Pool |
| `lap-swim.html` | [`6zQTQzGi…`](https://www.poolrelay.com/v/6zQTQzGiPiJDozzD145fnY) | lap swim in both pools, plus GCAT meets |
| `open-swim.html` | [`iZNfkEId…`](https://www.poolrelay.com/v/iZNfkEIdBqtovLPzM2QenD) | family open swim and Saturday water polo |
| `swim-lessons.html` | [`mnHnXReB…`](https://www.poolrelay.com/v/mnHnXReBBoGwMDzFfExuxx) | September and October group lessons; **Practice Groups** menu picks a level |
| `water-aerobics.html` | [`CtqIZEw9…`](https://www.poolrelay.com/v/CtqIZEw9hI2NZoYVkIBSmN) | the October water aerobics grid |
| `swim-teams.html` | [`BvBdRnqN…`](https://www.poolrelay.com/v/BvBdRnqNVFYAaFbSTwo8WB) | Low Country Aquatic Club, Chatham Kraken, water polo, GCAT meets |

## Sources (read 2026-09-25)

- **Hours** page: Lap Pool from Sept 8 (short course all day, closed 4–5:30pm Mon–Thu and 4–6pm Fri,
  Saturday "limited lanes" 7–noon), Recreation Pool from Aug 3 (adult lap swim and family open swim).
- **Home** page: the Sat Sept 26 GCAT Pentathlon closure (Lap Pool 8am–5pm), Saturday water polo pickup,
  weekly drop-in lessons (not entered: posted each Monday), open swim hours.
- **Water Aerobics** page: the October 2026 grid, with instructors.
- **Kraken** page: Mon/Wed 5:30–6:30pm, fall season 8/31–11/18, no practice 9/7 and 11/11.
- **RecDesk** program registration: 184 listings; the September and October group lesson sessions.
  Private and adaptive lessons (one-to-one slots) are not entered.
- **swimlcac.com/swimteam**: Low Country Aquatic Club's 2026–27 practice schedule for seven groups.

## What is ours

- **Lanes.** Lap Pool: 50 m, Long Course 8 lanes / Short Course 20 lanes (short course all fall); Recreation Pool 6
  lanes. Nothing says which lanes anyone uses, so lane numbers are our estimate.
- **Lessons grouped by time slot** and placed in the Recreation Pool; registration names no pool.
- **Club groups at the same time are one block** (e.g. Gold, Gold Lite and Navy Mon/Wed 4–5:30pm).
- **Sept 26**: Saturday lap swim, LCAC practice and water polo are skipped for the Pentathlon; lap swim
  7–8am and 5–6pm kept.
- Series start **Sept 8**, the date the current Lap Pool schedule took effect.

## Open questions (also on the hub page)

| | |
|---|---|
| **Gap** | When the "SLOW" times are; how many lanes LCAC takes during public lap swim (6–7:30am Tue/Thu, 2–3:30pm Mon–Thu, 5:30–7pm Tue/Thu/Fri). |
| **Conflict** | Evening open swim: 6:30 (home page) vs. 6:45 (Hours page). |
| **Gap** | Savannah Swim Team (2024 schedule), GCAT (no times), Savannah Masters (no times). |
| **Gap** | Saturday 12–6pm asterisk; Sundays not listed. |
| **Gap** | September water aerobics; water polo's pool. |
| **Conflict** | Short-course lanes: 24 (LCAC) vs. 20 (directories); Recreation Pool 50 yd (LCAC) vs. 25 yd (center). |
| **Overlap** | October Mon/Wed Jr. Stroke Stars 6:45–7:15pm vs. Adult Stroke Stars 7–7:30pm, left flagged. |
