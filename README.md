# NL Injury Tracker

## Community-Maintained MLB National League Injury Database

A structured, open-source database tracking injuries of National League MLB players. Community contributions are welcome!

### 📂 Repository Structure

```
nl-injury-tracker/
├── data/
│   └── injuries.json      # Main injury data (JSON format)
├── README.md               # This file
```

### 📊 Data Format

Each player entry in `data/injuries.json` includes:

| Field | Description |
|-------|-------------|
| `id` | Unique player identifier (slug) |
| `name` | Full player name |
| `team` | Current MLB team |
| `position` | Primary position |
| `injuries` | Array of injury records |
| `sources` | Array of source URLs for verification |

Each injury record includes:

| Field | Description |
|-------|-------------|
| `type` | Injury type (e.g., "ACL tear", "Ankle sprain") |
| `body_part` | Affected body part |
| `date_occurred` | Date of injury (ISO format) |
| `status` | Current status (e.g., "Rehabbing", "Recovering", "Active") |
| `severity` | Severity level (Minor / Moderate / Major) |
| `details` | Detailed description and timeline |
| `sources` | Verification links |

### 🌟 Current Featured Players (2025 Season Updates)

- **Ronald Acuña Jr.** (Atlanta Braves) — Tore left ACL May 2024; missed 2025 Opening Day (knee rehab). Returned May 23, 2025 — homered on first pitch after 362 days. Later dealt with hamstring strain (July-Aug) and Achilles issue (Aug). Late-September lineup dispute with manager Snitker (moved from leadoff). 2025 stats: .252/.362/.378; .331+ and 1.011 OPS over 43 games post-return.

- **Mookie Betts** (Los Angeles Dodgers) — Undiagnosed stomach illness early 2025 (lost ~20-25 lbs). Missed Opening Day and Japan series. Returned March 26, 2025. Changed to shortstop; battled swing mechanics and confidence through mid-2025 (career-low .258 AVG, .732 OPS). Strong late-season rebound (.317 over final 47 games). 2025 World Series champion; clutch two-run single in Game 6 to force Game 7.

- **Freddie Freeman** (Los Angeles Dodgers) — Right ankle surgery December 2024 (debridement + loose body removal). Gradual 2025 rehab; missed Tokyo Series, IL April 3-11 (ankle aggravation). Hit .376 through 30 games but suffered career-worst power slump (41-game HR drought May-June). All-Star nod. Neck stinger (Aug 27, out 2 days). 2025 World Series champion; walk-off HR in World Series Game 3 (second career WS walk-off). 2025 stats: .295/.367/.502, 147G, 24HR, 90RBI, 139 wRC+, 3.9 fWAR.

### 🤝 How to Contribute

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

### ⚖️ License

This project is open-source and available under the MIT License.