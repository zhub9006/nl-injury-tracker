# NL Injury Tracker

A community-maintained MLB National League injury database, tracking updates for NL stars and beyond.

## Purpose
This repository serves as a central, community-editable resource for tracking injury updates on National League players. It is designed to be kept up-to-date by contributors, providing a reliable historical and current record of player health statuses, injury timelines, and return information.

## How to Contribute
1. **Fork the repository** and create a new branch for your changes.
2. **Update or add** injury data in the appropriate file (`injury-updates.json` for machine-readable data, `LATEST-INFO.md` for human-readable summaries, `DETAILED-UPDATES.md` for extended career timelines).
3. **Submit a pull request** with a clear description of what was changed and why.
4. If reporting a new injury, include the **date**, **details**, **rehab timeline**, and **return status** and **source** where available.
5. **Always cross-reference** with official sources: MLB.com, team press releases, and recognized beat reporters.

## Players Currently Tracked
- **Ronald Acuña Jr.** — Atlanta Braves (Outfielder, Right Field)
- **Mookie Betts** — Los Angeles Dodgers (Shortstop / Multi-Position)
- **Freddie Freeman** — Los Angeles Dodgers (First Base)

## Quick Reference — Latest Updates (July 15, 2026)

| Player | Team | Status | Current Injury | Expected Return |
|--------|------|--------|---------------|-----------------|
| **Ronald Acuña Jr.** | Atlanta Braves | 🟡 On 60-Day IL (Rehabbing) | Left fibula fracture (Mar 3, 2026); prior knee issues | Early-to-mid July 2026 |
| **Mookie Betts** | Los Angeles Dodgers | 🟡 Day-to-Day (Active) | Stiff lower back (Jul 11) + wrist soreness (Jul 2); prior oblique strain | N/A — playing with management |
| **Freddie Freeman** | Los Angeles Dodgers | 🟢 Active & Healthy | Neck stinger (resolved Aug 2025); chronic ankle managed | N/A — currently playing |

---

### Ronald Acuña Jr. — Atlanta Braves (OF, RF)
- **Status:** 🟡 On 60-Day IL — Rehabbing. Cleared for BP/throwing/straight-line drills. **NOT cleared for cutting drills yet.**
- **Current:** Left fibula fracture (non-displaced), suffered Mar 3, 2026 in Spring Training
- **Est. Return:** Early-to-mid July 2026
- **History:** Left knee MCL sprain (Apr 2025), Left knee meniscus tear (Sep 2024, surgery), Left knee bone bruise (2023), Left hamstring strain (May 2025), Grade 1 calf strain (Jul 2025)
- **Pre-injury 2025 slash:** .252/.362/.378
- **Note:** First injury-shortened season since 2023 torn ACL. Rehab started Apr 2026. **Rehab Gate:** Must progress through BP → live pitching → straight-line running → cutting → MiLB rehab → MLB activation.
- **Manager Quote:** "He's probably as strong as he's ever been... When he comes back, we want him to be able to go. We're going to make sure he is ready to go when we do turn him loose." — Brian Snitker

### Mookie Betts — Los Angeles Dodgers (SS / Multi-Position)
- **Status:** 🟡 Day-to-Day (Active). NOT expected on IL for any current issues.
- **Current:** Stiff lower back (Jul 11, day-to-day); Right wrist soreness (resolved Jul 2)
- **Est. Return:** Within days (NOT expected on IL for either issue)
- **History:** Right wrist fracture (Mar 2025 — 6-8 weeks, pitching machine accident), Right oblique strain (Jul 2025), Viral illness (late Jul 2025 — 20 lbs loss), Left ankle sprain (Jun 2025)
- **Recent:** On 7-game hitting streak with .355 avg over last 15 games
- **Note:** Most tumultuous stretch in recent memory for a star player. All major injuries resolved. Conservative treatment; no IL expected for back or wrist.

### Freddie Freeman — Los Angeles Dodgers (1B)
- **Status:** 🟢 Active & Healthy. Chronic ankle managed with load management.
- **Current:** No acute injury. Neck stinger (Aug 2025) resolved. Chronic ankle managed.
- **Est. Return:** N/A — currently playing regularly
- **History:** Neck stinger (Aug 2025), Left rib/scar tissue (Mar 2025 — Tokyo), Left ankle sprain (Jun 2025), Right ankle sprain (Sep 2024 — debridement Dec 2024), Left thumb contusion (Aug 2024)
- **Note:** Chronic ankle issues require ongoing monitoring. Walk-Off Grand Slam in 2024 WS legend despite injuries.

---

## Data Format
- **`injury-updates.json`** — Full machine-readable injury database with current status, injury history, rehab timelines, and sources
- **`nl-injury-updates.json`** — Simplified JSON summary for quick consumption
- **`LATEST-INFO.md`** — Human-readable current injury updates with summary tables and detailed timelines
- **`DETAILED-UPDATES.md`** — Extended supplementary detail with career injury timelines and key context

## Repository Structure
- `injury-updates.json` — Full structured injury database
- `nl-injury-updates.json` — Simplified JSON summary
- `LATEST-INFO.md` — Human-readable summaries and quick reference
- `DETAILED-UPDATES.md` — Extended career injury timelines and supplementary data
- `README.md` — This file

## License
This project is open source and available for community use.