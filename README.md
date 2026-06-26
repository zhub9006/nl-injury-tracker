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
| `surgery_date` | Date of surgery if applicable (optional) |
| `status` | Current status (e.g., "Rehabbing", "Recovering", "Active") |
| `severity` | Severity level (Minor / Moderate / Major) |
| `details` | Detailed description and context |
| `rehab_note` | Additional rehab context (optional) |
| `personal_note` | Human-interest or personal context (optional) |
| `sources` | Verification links |

### ⚡ Current Featured Players (as of Oct 2025)

- **Ronald Acuña Jr.** (Atlanta Braves) — Left ACL tear (May 2024); second ACL surgery, rehabbing at 90-95%, expected to miss first month of 2025, no definitive return date set
- **Mookie Betts** (Los Angeles Dodgers) — Stomach illness (Mar 2025, lost ~20 lbs) + lower back pain (Apr 2026); bounced back from worst career season (.258 AVG) to postseason resurgence; season finished .258/.732
- **Freddie Freeman** (Los Angeles Dodgers) — Right ankle sprain + surgery (Sept 2024); re-injured in shower mishap (Mar 2025), returned with .376 AVG / 1.171 OPS; playing through daily treatment regimen

### 🔄 Latest Injury Updates

| Player | Injury | Latest Status | Key Date |
|--------|--------|---------------|----------|
| Ronald Acuña Jr. | Left ACL tear | Rehabbing — 90-95% recovery, may return late 2025 | Missing first month of 2025 |
| Mookie Betts | Stomach illness → Back pain | Recovered from illness; batting .317 to close out 2025 season | Illness: Mar 2025 |
| Freddie Freeman | Right ankle surgery | Active — .376 AVG despite daily treatment | Shower re-injury: Mar 31, 2025 |

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
- Prefer machine-readable single-line JSON for `injuries.json` (run `python -m json.tool --compact` before committing)

### ⚖️ License

This project is open-source and available under the MIT License.
