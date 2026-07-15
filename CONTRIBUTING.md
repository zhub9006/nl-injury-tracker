# Contributing to NL Injury Tracker

Thank you for your interest in contributing! This is a community-maintained MLB injury database.

## How to Contribute

### 1. Fork the Repository
Click the "Fork" button on the top-right of the [repository page](https://github.com/zhub9006/nl-injury-tracker), then clone your fork locally.

```bash
git clone https://github.com/YOUR_USERNAME/nl-injury-tracker.git
cd nl-injury-tracker
git checkout -b your-feature-branch
```

### 2. Update the Data Files
- **`INJURY-DATA.json`** — Update the machine-readable JSON for the player(s) you're reporting on.
- **`LATEST-INFO.md`** — Update the human-readable summary if the injury status has changed.
- Add new players in the same format as existing entries.

### 3. Include Required Information
When reporting an injury update, please include:
- **Date** of the injury or update
- **Injury type and details** (what happened, mechanism if known)
- **Rehab timeline** or expected return
- **Return status** (Day-to-Day, IL, Rehabbing, etc.)
- **Source** (URL to official report, team PR, beat reporter article)

### 4. Submit a Pull Request
- Use a clear commit and PR title (e.g., "Update Acuña fibula rehab progress - July 15")
- Describe what changed and why
- Reference source URLs
- Cross-reference with official sources (MLB.com, team PRs, beat reporters)

## Data Format Guidelines

### JSON Structure (`INJURY-DATA.json`)
```json
{
  "meta": {
    "last_updated": "YYYY-MM-DD",
    "total_players_tracked": N
  },
  "players": {
    "player-slug": {
      "name": "Full Name",
      "team": "Team Name",
      "position": "Positions",
      "status": "Current status",
      "status_color": "green|yellow|red",
      "current_injury": {
        "type": "Injury type",
        "date_reported": "YYYY-MM-DD",
        "mechanism": "How it happened",
        "severity": "Mild/Moderate/Severe",
        "details": "Additional details"
      },
      "rehab_timeline": {
        "started": "YYYY-MM",
        "expected_return": "Target date"
      },
      "injury_history": [
        {
          "date": "YYYY-MM-DD",
          "type": "Injury type",
          "return_status": "Returned/In Rehab/Day-to-Day"
        }
      ],
      "notes": "Community watch notes",
      "data_sources": ["URL1", "URL2"]
    }
  }
}
```

### Markdown Structure (`LATEST-INFO.md`)
- Maintain the Quick Reference Table at the top
- Use consistent emoji colors: 🟢 Active, 🟡 Day-to-Day/Recovering, 🔴 Out / IL
- Include injury history tables with dates
- Add manager quotes where available
- Note community watch items at the bottom

## Player-Specific Notes

### Ronald Acuña Jr. (ATL)
- Rehab progression: BP → live pitching → straight-line running → cutting drills → MiLB assignment → MLB
- Must be cleared for cutting drills before MLB activation
- Monitor Braves beat reporters (Mark Bowman, Journal Sentinel)

### Mookie Betts (LAD)
- Recurring oblique/back issues — conservative treatment
- NOT expected on IL unless severe
- Watch for stiffness after off-days

### Freddie Freeman (LAD)
- Chronic ankle — load management
- Neck stingers may recur
- Watch Dodgers lineup changes

## Code of Conduct
- Be respectful in PR reviews
- Only add information from verified sources
- If unsure, leave a note and let the community verify

## Questions?
Open an issue with the tag "question" and we'll help!