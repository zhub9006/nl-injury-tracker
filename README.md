# NL Injury Tracker

## Community-Maintained MLB National League Injury Database

A structured, open-source database tracking injuries of National League MLB players. Community contributions are welcome!

### 🏅 Latest Injury Updates (October 2025)

| Player | Injury | Latest Status | Key Date |
|--------|--------|---------------|----------|
| **Ronald Acuña Jr.** | ACL tear (left) → Hamstring strain → Achilles issue → Late-season slump | Recovered from injuries; on IL with mental/performance slump in Sept | ACL: May 2024; Hamstring: Jul 26, 2025; Achilles: Aug 2025 |
| **Mookie Betts** | Stomach illness → Oblique strain → Fractured toe → Lower back pain | Recovered from all injuries; career-worst regular season then playoff rebound | Illness: Mar 2025; Oblique: Apr 5, 2025; Toe: May 28, 2025; Back: Aug 4, 2025 |
| **Freddie Freeman** | Ankle sprain + surgery → Shower re-injury → Wrist contusion → Neck stinger | Fully recovered; postseason walk-off HR hero in 2025 WS | Ankle surgery: Dec 2024; Shower: Mar 2025; Wrist: Jul 20, 2025; Neck: Aug 27, 2025 |

### ⚡ Current Featured NL Stars

- **Ronald Acuña Jr.** (Atlanta Braves) — Torn left ACL (May 2024, 2nd surgery); returned May 23, 2025 after ~1 year rehab; Grade 1 left hamstring strain (Jul 2025); brief Achilles issue (Aug 2025); late-season mental slump (Sept 2025). At 90-95% recovered from ACL surgery as of February 2025.
- **Mookie Betts** (Los Angeles Dodgers) — Undiagnosed stomach illness (Mar 2025, lost ~20 lbs); right oblique strain (Apr 2025, missed 32 games); fractured left toe (May/Jun 2025); lower back pain (Aug 2025). Rediscovered form in playoffs after career-worst regular season (.258 AVG). Dodgers won 2025 World Series.
- **Freddie Freeman** (Los Angeles Dodgers) — Right ankle sprain + surgery (Sept-Dec 2024); "shower mishap" re-injury (Mar 2025, 10-day IL); left wrist contusion (Jul 2025); neck stinger (Aug 2025). Plays through daily ~1.5hr maintenance regimen. Dodgers won 2025 World Series with walk-off HR.

### 📁 Repository Structure

```
nl-injury-tracker/
├── data/
│   └── injuries.json      # Main injury data (JSON format)
├── README.md               # This file
└── LICENSE                 # MIT License
```

### 📊 Data Format

Each player entry in `data/injuries.json` includes:

| Field | Description |
|-------|-------------|
| `id` | Unique player identifier (slug) |
| `name` | Full player name |
| `team` | Current MLB team |
| `position` | Primary position |
| `jersey_number` | Jersey number |
| `season_stats_2025` | Season statistics for context |
| `injuries` | Array of injury records |
| `sources` | Verification links |

Each injury record includes:

| Field | Description |
|-------|-------------|
| `type` | Injury type (e.g., "ACL tear", "Ankle sprain") |
| `body_part` | Affected body part |
| `date_occurred` | Date of injury (ISO format) |
| `date_returned` | Date player returned to lineup |
| `status` | Current status (e.g., "Recovered", "Active", "Surgery Required") |
| `severity` | Severity level (Minor / Moderate / Major) |
| `details` | Detailed description and context |
| `sources` | Verification links |

### 🔗 How to Contribute

1. Fork this repository
2. Add or update player injury data in `data/injuries.json`
3. Include credible source URLs for verification
4. Submit a Pull Request with a clear description of changes

### ✅ Contribution Guidelines

- Only include **verifiable, sourced** injury information
- Use **ISO 8601 date format** (YYYY-MM-DD)
- Keep `details` fields factual and concise
- Add new players to the `players` array following the existing schema
- Update `metadata.last_updated` when making changes
- Prefer machine-readable single-line JSON for `injuries.json` (run `python -m json.tool --compact` before committing)

### ⚖️ License

This project is open-source and available under the MIT License.

## Links

- **GitHub:** https://github.com/zhub9006/nl-injury-tracker
- **Clone:** `git clone https://github.com/zhub9006/nl-injury-tracker.git`