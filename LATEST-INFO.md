# 🏥 NL Injury Tracker — Latest Updates

> **Last updated:** July 27, 2026 | Community-maintained MLB National League injury database

This file contains the latest injury updates for the three National League stars currently tracked by this repository. All information is sourced from MLB.com, ESPN, AP News, Dodgers Nation, Dodgers Beat, and other MLB media outlets.

---

## 🟠 Ronald Acuña Jr. — Atlanta Braves (Outfielder, Right Field)

| Field | Detail |
|-------|--------|
| **Current Status** | 🟡 **On 60-day IL** — rehab in progress |
| **Injury** | Left fibula fracture |
| **Injury Date** | March 3, 2026 |
| **Mechanism** | Crashed into outfield wall at Truist Park (Braves vs. Pirates) |
| **Surgery** | Required surgery to repair left fibula |
| **Rehab Start** | June 23, 2026 — FCL Braves (North Port, FL) |
| **Expected Return** | Early-to-mid July 2026 |
| **Confidence** | Moderate-High (rehab assignment underway) |

### Key Notes
- **Career injury history:** Right ACL tear (2021), Left ACL tear (2024), Left hamstring strain re-aggravation (June 2025), Left hamstring strain (May 2025), **Left fibula fracture (March 2026)** — this is his **5th career lower-body injury**.
- Two surgically repaired knees (both ACLs). When healthy, produces at .275/.394/.462 with 25 HR / 25 SB.
- 2023 MVP season: 41 HR, 73 SB. Braves signed Ha-Seong Kim to a $20M 1-year deal to cover SS in Acuña's absence.
- Manager Walt Weiss confirmed Acuña will return to the leadoff spot upon activation.
- Missed entire 2026 spring training and Cactus League due to the fibula fracture.
- Rehab assignment began June 23, 2026. In first game: struck out, flied out, reached on error — rehab expected to be relatively short.

### Sources
- MLB.com (Mark Bowman, Braves Beat; Jon Heyman), Atlanta Braves official communications, Forbes, CrunchSports, Yahoo Sports, AP News

---

## 🔵 Mookie Betts — Los Angeles Dodgers (Shortstop / Multi-Position)

| Field | Detail |
|-------|--------|
| **Current Status** | 🟢 **Active & Healthy** — playing shortstop |
| **Current Injury** | None |
| **Last Significant Injury** | Right oblique strain + non-displaced right fibula fracture |
| **Injury Date** | April 5, 2026 |
| **Mechanism** | Exited game vs. Washington Nationals with right oblique strain; imaging revealed fibula fracture |
| **IL Stint** | 10-day IL (April 5) → 60-day IL extension (oblique + fibula) |
| **Activation Date** | May 11, 2026 (~5 weeks missed) |
| **Return Performance** | 2-for-13 with HR in first 3 games back; "oblique is behind him" (self-reported May 14) |
| **Confidence** | High — playing regularly with no restrictions |

### Key Notes
- **Recent injury history:** Gastric/stomach illness (March 2025 — lost ~18 lbs), left toe fracture (May 2025), undisclosed illness scratch (July 2025), **right oblique strain + fibula fracture (April 2026)**.
- 8-time All-Star, 6-time Gold Glove winner, 4-time World Series champion. 2018 NL MVP.
- Lineup: batting #3 behind Ohtani, ahead of Freeman. To accommodate Kyle Tucker at #2.
- Dodgers are 26-12 as of mid-July 2026, tied for best record in MLB.
- Betts' return to the Dodgers lineup is one of the biggest positive storylines for the 2026 season.
- Contract: Signed through 2032 (long-term).

### Sources
- MLB.com, ESPN, Dodgers Nation, Dodgers Beat, True Blue LA, ClutchPoints, Dave Roberts post-game interviews

---

## 🔴 Freddie Freeman — Los Angeles Dodgers (First Base / Left Field)

| Field | Detail |
|-------|--------|
| **Current Status** | 🟢 **Active & Healthy** — managing chronic ankle issues (mono) |
| **Current Injury** | None |
| **Last Significant Injury** | Neck stinger (cervical nerve recurring issue) |
| **Injury Date** | August 27, 2025 |
| **Mechanism** | Stinger running from neck into right shoulder — recurring issue |
| **Additional History** | Left ankle surgery (Dec 2024), bone spur surgery (2026 spring training), left wrist contusion (May 2026 — HBP) |
| **Recent Status** | Activated off 60-day IL June 1, 2026 (.336 in 16 rehab games) |
| **Current Batting** | 2025: .302/.373/.501, 18 HR, 75 RBI in 94 games (.292 avg led NL) |
| **Confidence** | High — currently playing with no restrictions |

### Key Notes
- **Recurring neck stinger (cervical nerve issue)** must be monitored — Freeman was scratched Aug. 27, 2025 for a one-game issue. Expected to return by Friday. Dodgers had off day to manage.
- Chronic ankle issues from 2024 postseason injury (debridement + loose body removal in Dec 2024). Also had bone spur surgery in 2026 spring training.
- 2026 wrist contusion (HBP vs. Brewers, late May) was minor — X-rays negative, quick return.
- Committed to batting title pursuit in 2025 (.292 AVG led NL).
- Lineup: batting #2-3, versatile in multi-position roles to accommodate lineup flexibility.
- Contract: Signed through long-term extension.

### Sources
- AP News, USA Today, ESPN, Dodgers Nation, Dodgers Beat, Bill Plunkett, Dave Roberts post-game, MLB.com

---

## 📊 Summary Timeline (Recent)

| Date | Player | Event |
|------|--------|-------|
| March 3, 2026 | Ronald Acuña Jr. | Left fibula fracture (wall crash, surgery) |
| April 5, 2026 | Mookie Betts | Right oblique strain + non-displaced fibula fracture (IL) |
| May–June 2026 | Freddie Freeman | Left wrist contusion (HBP), resolved quickly |
| May 11, 2026 | Mookie Betts | Activated from IL, ~5 weeks missed |
| June 1, 2026 | Freddie Freeman | Activated off 60-day IL (ankle surgery recovery) |
| June 23, 2026 | Ronald Acuña Jr. | FCL rehab assignment began |
| Mid-July 2026 | All three | Acuña expected return; Betts & Freeman active |

---

## 🛠 How to Contribute

1. **Fork the repository** and create a new branch for your changes.
2. **Update** `injury-updates.json` or add new player entries.
3. **Submit a pull request** with a clear description of what changed and your source(s).
4. If reporting a new injury, include **date**, **details**, **rehab timeline**, and **source**.

## 📄 Data Format

See `injury-updates.json` for the full machine-readable database. Each player entry includes:
- `name`, `team`, `position`, `status`
- `current_injury` (or `null` if healthy)
- `injury_history` — chronological list
- `rehab_timeline` — key milestones
- `return_status` — current return outlook with confidence level
- `notes` — additional context (contract, team outlook, etc.)
- `data_sources` — where the information was gathered
