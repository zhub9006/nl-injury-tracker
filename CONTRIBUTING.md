# Contributing to NL Injury Tracker

Thank you for your interest in contributing to this community-maintained MLB National League injury database! This guide will help you get started.

## How to Contribute

### 1. Fork the Repository
Click the "Fork" button at the top-right of the repository page to create your own copy.

### 2. Create a Branch
Create a new branch for your changes:
```bash
git checkout -b update-injury-data-for-betts
```

### 3. Make Your Changes
Update the relevant data files with the latest verified injury information:
- **`INITIAL-DATA.md`** — Full injury reports with timelines, stats, manager quotes, and rehab progress
- **`NL-STAR-INJURY-UPDATES-LATEST.md`** — Quick-reference summary table and bullet-point updates

### 4. Follow Data Guidelines
When reporting an injury update, include:
- **Date** of the update or the injury event
- **Details** of the injury (type, grade/severity if known, body part, mechanism)
- **Current status** (active, IL, rehabbing, day-to-day, etc.)
- **Rehab progress** (milestones, rehab assignments, gate clearances)
- **Expected return** timeline or target date
- **Source(s)** — Official team reports, MLB.com, ESPN, team press conferences, beat reporters
- **Manager/coach quotes** where available

### 5. Cross-Reference Everything
Always verify against at least 2 independent sources. Preferred sources include:
- MLB.com official injury reports
- Team press releases and official social media
- ESPN injury beat
- The Athletic / SI.com
- Recognized beat reporters (Mark Bowman, Jared Diamond, etc.)
- Manager/coach press conference quotes

### 6. Submit a Pull Request
Open a PR against the `main` branch with:
- A clear title (e.g., "Update Acuña rehab status — joined Gwinnett")
- A description of what changed and why
- Source citations
- Screenshots or links where helpful

## Reporting New Players

Want to track a new NL player? Fork the repo and:
1. Add their section to `INITIAL-DATA.md` following the existing format
2. Add their entry to the quick-reference table in `NL-STAR-INJURY-UPDATES-LATEST.md`
3. Include their basic injury history if you have it
4. Submit a PR with a clear description

## Code of Conduct
- Be respectful and constructive in discussions
- Always cite sources and never fabricate information
- Update data promptly when new information becomes available
- When in doubt, leave a comment asking for clarification rather than guessing

## Getting Help
- Open an [Issue](https://github.com/zhub9006/nl-injury-tracker/issues) for questions or bug reports
- Check existing issues before opening a new one
- Join the discussion in active PRs

---
*This is a community project. Every contribution helps keep NL fans informed!*