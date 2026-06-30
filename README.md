# NL Injury Tracker

## Community-Maintained MLB National League Injury Database

A structured, open-source database tracking injuries of National League MLB players. Community contributions are welcome!

### 🆕 Latest Injury Updates (August 2025)

| Player | Injury | Latest Status | Key Date |
|--------|--------|---------------|----------|
| **Ronald Acuña Jr.** | Left ACL tear + Grade 1 Left Hamstring strain | Rehabbing — hamstring may keep him out through All-Star break | ACL surgery: Jun 2024; Hamstring: Jun 10, 2025 |
| **Mookie Betts** | Undiagnosed stomach illness → Oblique strain → Fractured toe → Lower back pain | Recovered from illness/toe; day-to-day with back; batting .330/.405/.454 since Aug. 5 | Illness: Mar 2025; Back: Aug 4, 2025 |
| **Freddie Freeman** | Right ankle sprain + surgery → Shower re-injury → Wrist contusion → Neck stinger | Active; uses daily 1.5hr treatment regimen; neck stinger resolved quickly | Ankle surgery: Dec 2024; Neck stinger: Aug 27, 2025 |

### ⚡ Current Featured NL Stars

- **Ronald Acuña Jr.** (Atlanta Braves) — Torn left ACL (May 2024, 2nd surgery); returned May 23, 2025 after ~1 year rehab; now on IL with Grade 1 left hamstring strain (June 2025), may not return until after All-Star break. At 90-95% recovered from ACL surgery as of February 2025.
- **Mookie Betts** (Los Angeles Dodgers) — Undiagnosed stomach illness (Mar 2025, lost ~20 lbs); right oblique strain (Apr 2025, missed 32 games); fractured left toe (May/Jun 2025); lower back pain (Aug 2025). Rediscovered form with .330/.405/.454 slash since August 5.
- **Freddie Freeman** (Los Angeles Dodgers) — Right ankle sprain + surgery (Sept-Dec 2024); "shower mishap" re-injury (Mar 2025, 10-day IL); returned strong at .376 AVG / 1.171 OPS; left wrist contusion (Jul 2025); neck stinger (Aug 2025); playing through daily ~1.5hr maintenance regimen.

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
| `injuries` | Array of injury records |
| `sources` | Array of source URLs for verification |

Each injury record includes:

| Field | Description |
|-------|-------------|
| `type` | Injury type (e.g., "ACL tear", "Ankle sprain") |
| `body_part` | Affected body part |
| `date_occurred` | Date of injury (ISO format) |
| `surgery_date` | Date of surgery if applicable (optional) |
| `status` | Current status (e.g., "Rehabbing", "Recovering", "Active") |
| `severity` | Severity level (Minor / Moderate / Major) |
| `details` | Detailed description and context |
| `rehab_note` | Additional rehab context (optional) |
| `personal_note` | Human-interest or personal context (optional) |
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