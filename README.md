# NL Injury Tracker

A community-maintained MLB National League injury database, tracking updates for NL stars and beyond.

## Purpose

This repository serves as a central, community-editable resource for tracking injury updates on National League players. It is designed to be kept up-to-date by contributors, providing a reliable historical and current record of player health statuses, injury timelines, and return information.

## How to Contribute

1. **Fork the repository** and create a new branch for your changes.
2. **Update or add** injury data in the appropriate JSON file.
3. **Submit a pull request** with a clear description of what was changed and why.
4. If reporting a new injury, include the **date**, **details**, **rehab timeline**, and **source** where available.

## Data Format

Each player entry includes:
- **name**: Full player name
- **team**: Current team
- **position**: Playing position
- **status**: Overall current status (Active, IL, Rehab, etc.)
- **current_injury**: Details of any active injury
- **injury_history**: Chronological list of past injuries
- **rehab_timeline**: Key dates and milestones in recovery
- **return_status**: Latest update on return-to-play expectations
- **notes**: Additional context

## Players Currently Tracked

- **Ronald Acuña Jr.** — Atlanta Braves
- **Mookie Betts** — Los Angeles Dodgers
- **Freddie Freeman** — Los Angeles Dodgers

## Latest Updates (as of July 20, 2026)

| Player | Injury | Status |
|--------|--------|--------|
| Ronald Acuña Jr. | Left fibula fracture (suffered March 3, 2026) | On 60-day IL; rehab assignment with FCL Braves began June 23, 2026; expected return early-to-mid July 2026 |
| Mookie Betts | Right oblique strain + non-displaced right fibula fracture (April 5, 2026) | Activated May 11, 2026; currently healthy and playing shortstop |
| Freddie Freeman | Left ankle issues (chronic); left wrist contusion (late May 2026, resolved) | Activated off 60-day IL June 1, 2026; batting .326 with 4 HR in late-June appearances |

## License

This project is open source and available for community use.

## Repository Structure

### Files
- [injury-updates.json](injury-updates.json) — Full injury database in JSON format
- [README.md](README.md) — This file