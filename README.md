# NL Injury Tracker

A community-maintained MLB National League injury database, tracking updates for NL stars and beyond.

## Purpose

This repository serves as a central, community-editable resource for tracking injury updates on National League players. It is designed to be kept up-to-date by contributors, providing a reliable historical and current record of player health statuses, injury timelines, and return information.

## How to Contribute

1. **Fork the repository** and create a new branch for your changes.
2. **Update or add** injury data in the appropriate file (`injury-updates.json` for machine-readable data, `LATEST-INFO.md` for human-readable summaries).
3. **Submit a pull request** with a clear description of what was changed and why.
4. If reporting a new injury, include the **date**, **details**, **rehab timeline**, and **source** where available.

## Data Format

- **`injury-updates.json`** — Full machine-readable injury database. Each player entry includes: name, team, position, status, current_injury, injury_history, rehab_timeline, return_status, notes, and data_sources.
- **`LATEST-INFO.md`** — Human-readable current injury updates for all tracked players with summary tables and timelines.

## Players Currently Tracked

- **Ronald Acuña Jr.** — Atlanta Braves (Outfielder, Right Field)
- **Mookie Betts** — Los Angeles Dodgers (Shortstop / Multi-Position)
- **Freddie Freeman** — Los Angeles Dodgers (First Base)

## Latest Updates

See [LATEST-INFO.md](LATEST-INFO.md) for a human-readable summary of the latest injuries, returns, and timelines.

### Quick Reference (as of July 2026)

| Player | Current Status | Latest Injury | Expected Return |
|--------|---------------|---------------|-----------------|
| **Ronald Acuña Jr.** | 🟡 On 60-day IL (rehab) | Left fibula fracture (March 3, 2026) | Early-to-mid July 2026 |
| **Mookie Betts** | 🟢 Active & Healthy | Right oblique strain + fibula fracture (resolved) | N/A — currently playing |
| **Freddie Freeman** | 🟢 Active & Healthy | Neck stinger (Aug 2025, resolved); chronic ankle (managed) | N/A — currently playing |

## Repository Structure

### Files
- [injury-updates.json](injury-updates.json) — Full injury database in JSON format (14.0 KB)
- [LATEST-INFO.md](LATEST-INFO.md) — Human-readable injury summaries and quick reference
- [README.md](README.md) — This file

## License

This project is open source and available for community use.