# NL Injury Tracker ⚾🏥

A community-maintained MLB National League injury database, tracking updates for NL stars and beyond.

## Purpose
This repository serves as a central, community-editable resource for tracking injury updates on National League players. It is designed to be kept up-to-date by contributors, providing a reliable historical and current record of player health statuses, injury timelines, and return information.

## Quick Reference — Latest Updates (July 2026)

| Player | Team | Status | Current Injury | Expected Return |
|--------|------|--------|---------------|-----------------|
| **Ronald Acuña Jr.** | Atlanta Braves | 🟡 Rehabbing (Triple-A) | Left hamstring strain (recurring); left fibula fracture (resolved) | July 22–23, 2026 |
| **Mookie Betts** | Los Angeles Dodgers | 🟡 Day-to-Day (Active) | Stiff lower back (Jul 11) + wrist soreness (Jul 2); prior oblique strain | Within days |
| **Freddie Freeman** | Los Angeles Dodgers | 🟢 Active & Healthy | Neck stinger (resolved Aug 2025); chronic ankle managed | N/A — currently playing |

---

### Ronald Acuña Jr. — Atlanta Braves (OF, RF)
- **Status:** 🟡 Rehabbing at Triple-A Gwinnett. Cleared for all rehab gates including cutting drills.
- **Current:** Left hamstring strain (2nd occurrence, Jun 2025) + left fibula non-displaced fracture (Mar 3, 2026 Spring Training — resolved). Hit grand slam in 3rd FCL rehab game (423 ft, 112.8 mph).
- **Est. Return:** July 22–23, 2026
- **History:** Left knee MCL sprain (Apr 2025), Left knee meniscus tear (Sep 2024, surgery), Left knee bone bruise (2023), Left hamstring strain (May 2025), Grade 1 calf strain (Jul 2025), Left ACL tear (May 2024), Right ACL tear (Jun 2021)
- **Manager Quote:** *"He's probably as strong as he's ever been... When he comes back, we want him to be able to go. We're going to make sure he is ready to go when we do turn him loose."* — Walt Weiss

### Mookie Betts — Los Angeles Dodgers (SS / Multi-Position)
- **Status:** 🟡 Day-to-Day (Active). NOT expected on IL for any current issues.
- **Current:** Stiff lower back (Jul 11, day-to-day); Right wrist soreness (resolved Jul 2). Post-viral fatigue from late Jul 2025 (~25 lbs loss). On 7-game hitting streak (.355 avg over last 15).
- **Est. Return:** Within days (NOT expected on IL)
- **History:** Right wrist fracture (Mar 2025 — 6-8 weeks), Right oblique strain (Jul 2025 + Apr 2026), Viral illness (late Jul 2025 — 25 lbs loss), Death of stepfather (personal leave), Left ankle sprain (Jun 2025)
- **Note:** Most tumultuous stretch in recent memory for a star player. All major injuries resolved. Conservative treatment; no IL expected.

### Freddie Freeman — Los Angeles Dodgers (1B)
- **Status:** 🟢 Active & Healthy. Chronic ankle managed with load management.
- **Current:** No acute injury. Neck stinger (Aug 2025) resolved. Chronic ankle managed with load management. Left wrist contusion (HBP) resolved.
- **Est. Return:** N/A — currently playing regularly
- **History:** Neck stinger (Aug 2025), Left ankle sprain (Jun 2025), Left rib/scar tissue (Mar 2025 — Tokyo), Left wrist contusion (HBP, Aug 2025), Right ankle sprain (Sep 2024 — debridement Dec 2024), Left thumb contusion (Aug 2024)
- **Note:** Chronic ankle issues require ongoing load management. Walk-Off Grand Slam in 2024 WS legend despite injuries.

---

## How to Contribute

1. **Fork the repository** and create a new branch for your changes.
2. **Update or add** injury data in [`INJURY-DATA.json`](INJURY-DATA.json) (machine-readable) and/or [`NL-STAR-INJURY-UPDATES.md`](NL-STAR-INJURY-UPDATES.md) (human-readable).
3. **Submit a pull request** with a clear description of what was changed and why.
4. If reporting a new injury, include the **date**, **details**, **rehab timeline**, **return status**, and **source** where available.
5. **Always cross-reference** with official sources: MLB.com, team press releases, and recognized beat reporters.

## Data Files

| File | Type | Description |
|------|------|-------------|
| [`NL-STAR-INJURY-UPDATES.json`](NL-STAR-INJURY-UPDATES.json) | Machine-readable JSON | **Initial inaugural data file** — Structured injury database with current status, injury history, rehab timelines, and sources for all tracked NL stars |
| [`NL-STAR-INJURY-UPDATES.md`](NL-STAR-INJURY-UPDATES.md) | Human-readable Markdown | **Inaugural summary** — Expanded bullet-point format with quick-reference tables and detailed timelines |
| [`INJURY-DATA.json`](INJURY-DATA.json) | Machine-readable JSON | **Primary ongoing database** — Full structured injury database (continuously updated) |
| [`nl-injury-updates.json`](nl-injury-updates.json) | Simplified JSON | Lightweight JSON summary for quick consumption by apps/scripts |
| [`LATEST-INFO.md`](LATEST-INFO.md) | Human-readable | Current injury updates with quick-reference tables and detailed timelines |
| [`RESEARCH-UPDATES.md`](RESEARCH-UPDATES.md) | Human-readable | Research-based detailed updates with latest sources and rehab gate progress |
| [`DETAILED-UPDATES.md`](DETAILED-UPDATES.md) | Human-readable | Extended career injury timelines and supplementary data |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | Documentation | Community contribution guidelines and format standards |

## Players Currently Tracked

| Player | Team | Position | League |
|--------|------|----------|--------|
| Ronald Acuña Jr. | Atlanta Braves | RF / DH | NL |
| Mookie Betts | Los Angeles Dodgers | SS / 3B / OF | NL |
| Freddie Freeman | Los Angeles Dodgers | 1B | NL |

Want to add more players? Fork the repo and submit a PR with their injury data in [`INJURY-DATA.json`](INJURY-DATA.json).

## License
This project is open source and available for community use.