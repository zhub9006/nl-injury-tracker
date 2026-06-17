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
| `details` | Detailed description and context |
| `sources` | Verification links |

### 🌟 Current Featured Players

- **Ronald Acuña Jr.** (Atlanta Braves) — Left ACL tear (2024); rehabbing, no definitive return date
- **Mookie Betts** (Los Angeles Dodgers) — Stomach illness (2025) + lower back pain (2026); recovering/evaluating
- **Freddie Freeman** (Los Angeles Dodgers) — Right ankle sprain + surgery (2024); recovering

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
