# Research Sources — July 2026 Injury Update Session

> **Sources used for the July 2026 injury data compilation for Ronald Acuña Jr., Mookie Betts, and Freddie Freeman**

---

## Ronald Acuña Jr. — Atlanta Braves

| Source | URL | Data Point |
|--------|-----|------------|
| MLB.com — Braves injuries and roster moves | https://www.mlb.com/news/braves-injuries-and-roster-moves | Latest IL status, rehab dates, injury chronology |
| MLB.com — Acuña hits grand slam in rehab | https://www.mlb.com/news/ronald-acuna-jr-hits-grand-slam-during-rehab-assignment | FCL rehab: 423 ft grand slam, 112.8 mph exit velo |
| MLB.com MiLB — Gwinnett game logs | Triple-A Gwinnett | July 18–19 rehab games, 1-for-4 in RF debut, 1-for-4 in 2nd game |
| ESPN / RotoWire | https://www.rotowire.com/baseball/player/ronald-acuna-14200 | Acuna's first 8 games after May return: 3 HR; midseason calf strain |
| AP News — Acuña placed on IL | https://apnews.com/article/braves-acuna-hamstring-injured-list-ed293022f281a4f8312eb3f3e8331e9d | Left hamstring strain, June 9 |
| Brian Snitker press conference | Quote: "He's probably as strong as he's ever been" | Manager confidence in return timeline |

---

## Mookie Betts — Los Angeles Dodgers

| Source | URL | Data Point |
|--------|-----|------------|
| Dodger Blue — Wrist injury update | https://dodgerblue.com/mookie-betts-right-wrist-soreness-expected-back-dodgers-game-thursday/2026/07/02/ | Wrist soreness July 2, returned for Padres series; July 11 back issues reported |
| MLB.com — Betts returns from illness | https://www.mlb.com/news/mookie-betts-returns-from-illness-and-struggles | Multi-level toll: illness, stepfather's death, back injury |
| MLB.com — Oblique rehab timeline | https://www.mlb.com/news/mookie-betts-dodgers-oblique-rehab-timeline | Rehab assignment at Triple-A OKC, 1-for-3, 5 IP SS |
| Sporting News — Return timeline | https://www.sportingnews.com/us/mlb/los-angeles-dodgers/news/dodgers-mookie-betts-return-timeline-revealed-dave-roberts/ | Oblique strain from April 4 vs Nationals, 5+ week IL stint |
| SI.com — Dave Roberts return timeline | https://www.si.com/mlb/dodgers/onsi/dodgers-dave-roberts-finally-reveals-mookie-betts-return-timeline | Oblique injury details, return expectations |
| IBTimes — Oblique recovery slows Dodgers | https://www.ibtimes.com.au/mookie-betts-injury-update-oblique-strain-recovery-slows-dodgers-star-remains-weeks-return-1867329 | Early stages of baseball-specific activities |
| Dave Roberts press conferences | Various | "Managing day-to-day" for back, "turned a corner" for illness |
| MLB Trade Rumors — Latest update | https://www.newsbreak.com/news/4638258040337-mookie-betts-injury-update-latest-rumors-on-dodgers-star-s-status-timeline-to-return | July 2026 latest status |

---

## Freddie Freeman — Los Angeles Dodgers

| Source | URL | Data Point |
|--------|-----|------------|
| LAFB Network — Encouraging Update | https://www.lafbnetwork.com/mlb/la-dodgers/la-dodgers-news/los-angeles-dodgers-freddie-freeman-injury-status/ | Offseason ankle surgery recovery, Spring Training timeline, jersey #5 |  ```json
{
  "meta": {
    "database_name": "NL Injury Tracker — July 2026 Update",
    "description": "Updated seed data incorporating latest July 2026 research including Acuna's FCL+Gwinnett rehab progress, Betts' back/wrist status, and Freeman's chronic ankle management.",
    "last_updated": "2026-07-22",
    "version": "2.1.0",
    "total_players": 3,
    "league": "National League",
    "sources": [
      "MLB.com",
      "MLB.com MiLB",
      "Dodger Blue",
      "LAFB Network",
      "Forbes Sports",
      "ESPN",
      "The Athletic",
      "USA Today",
      "MLB Trade Rumors",
      "Yahoo Sports",
      "CBS Sports",
      "Sporting News",
      "SI.com",
      "IBTimes",
      "AP News",
      "RotoWire",
      "Atlanta Braves official announcements",
      "Dave Roberts press conferences",
      "Brian Snitker press conference"
    ]
  },
  "injury_updates": [
    {
      "player": "Ronald Acuña Jr.",
      "team": "Atlanta Braves",
      "position": "RF / DH",
      "jersey": 13,
      "status": "rehabbing_gwinnett",
      "status_detail": "On rehab assignment at Triple-A Gwinnett; all rehab gates cleared; hit grand slam in FCL game (423 ft, 112.8 mph); expected MLB activation July 22-23, 2026",
      "current_injury": {
        "primary": "Grade 1 left hamstring strain (2nd occurrence, June 9 2025)",
        "secondary": "Left fibula non-displaced fracture (March 3, 2026 — RESOLVED)",
        "date_acquired": "2025-06-09",
        "mechanism": "Strained running to first base vs Rockies",
        "severity": "moderate",
        "rehab_location": "FCL Braves → Triple-A Gwinnett"
      },
      "rehab_gates": {
        "bp_throwing_straight_line": "cleared",
        "cutting_drills": "cleared",
        "outfield_work": "cleared",
        "milib_rehab": "in_progress - Gwinnett July 17-19",
        "mlb_activation": "pending - expected July 22-23, 2026",
        "grand_slam_fcl": "423 ft, 112.8 mph exit velocity",
        "rehab_rf_debut": "July 19, 2026 (first Gwinnett RF game)",
        "second_gwinnett_game": "July 21, 2026 (1-for-4, single)"
      },
      "rehab_progress": {
        "fcl_start": "2026-07-13",
        "gwinnett_transfer": "2026-07-17",
        "gwinnett_games_played": ["July 18", "July 19 (RF debut)", "July 21"],
        "gwinnett_stats": ".143 (1-for-7 plus), 1 HR, 5 RBI, .904 OPS in FCL; .250 (4-for-16) at Gwinnett",
        "grand_slam_fcl": "423 ft, 112.8 mph exit velocity"
      },
      "expected_return": "2026-07-22/23",
      "key_stats": {
        "pre_injury_2025_slash": ".251/.333/.477",
        "pre_injury_2025_games": 53,
        "pre_injury_2025_hr": 7,
        "pre_injury_2025_rbi": 22,
        "pre_injury_2025_sb": 15,
        "gwinnett_career_stats": ".313/.342/.865 (88 games)"
      },
      "history": [
        "2025-07-30: Grade 1 calf strain (resolved)",
        "2025-06-09: Left hamstring strain 2nd — onset vs Rockies",
        "2025-05: Left hamstring strain 1st (resolved)",
        "2025-04-28: Left knee MCL sprain (resolved)",
        "2024-09: Left knee meniscus tear surgery (resolved)",
        "2024-05-26: Left ACL tear surgery (resolved, ~8 months)",
        "2024-03: Left fibula non-displaced fracture (resolvable)",
        "2021-06: Right ACL tear surgery (resolved)"
      ],
      "manager_quote": "He's probably as strong as he's ever been.",
      "sources": ["MLB.com", "MLB.com MiLB", "Atlanta Braves announcements", "Walt Weiss press conference", "RotoWire"]
    },
    {
      "player": "Mookie Betts",
      "team": "Los Angeles Dodgers",
      "position": "SS / 3B / OF",
      "jersey": 50,
      "status": "active_day_to_day",
      "status_detail": "Active with day-to-day management; NOT expected on IL; post-viral fatigue from July 2025 illness stabilizing; rebellious to recovery month of June (.290/.339/.477)",
      "current_injury": {
        "primary": "Stiff lower back (July 11, day-to-day)",
        "secondary": "Right wrist soreness (resolved July 2, 2026)",
        "chronic": "Residual post-viral fatigue (~25 lbs loss, late Jul 2025; weight recovering)",
        "mechanism": "Back stiffness — non-specific; wrist soreness resolved with treatment; viral illness (suspected norovirus)",
        "severity": "minor",
        "expected_il": false
      },
      "recent_form": {
        "hitting_streak": "7 games",
        "avg_last_15": ".355",
        "july_2026_daily_tracking": "Day-to-day back management",
        "june_2026_month": ".290/.339/.477, 5 HR, 12 RBI in 26 games (115 PA)",
        "last_12_games": "19-for-51 (.373), 7 extra-base hits, 10 RBI"
      },
      "rehab_progress": {
        "back_out_games": 3,
        "wrist_resolved": "2026-07-02",
        "wrist_missed_games": 1,
        "il_expected": false,
        "illness_type": "Norovirus (suspected)",
        "illness_weight_loss": "~25-30 lbs (175→150 lbs, now ~175 lbs)",
        "illness_recovery": "COVID-era absent; stomach bug; full eating solids Mar 15 return"
      },
      "expected_return": "Within days (no IL expected)",
      "key_stats": {
        "2025_slash": ".258/.326/.406",
        "2025_wrc_plus": 104,
        "month_of_jun_2026": ".290/.339/.477, 5 HR, 12 RBI",
        "late_jun_2026_form": "Below .200 as of June 13 then broke out; 7-game hitting streak"
      },
      "history": [
        "2026-07-11: Stiff lower back (day-to-day)",
        "2026-07-02: Right wrist soreness (resolved)",
        "2026-04-05: Right oblique strain, 10-day IL (resolved, activated May 11)",
        "2025-03 (late): Norovirus stomach illness (~25-30 lbs loss, 175→150 lbs)",
        "2025-07 (late): Death of stepfather (personal leave)",
        "2025-03: Right wrist fracture, 6-8 weeks (resolved)",
        "2025: Fractured 4th toe, left foot (played through)",
        "2025: Right lower back strain (resolved)",
        "2024-06: Left ankle sprain (resolved)",
        "2024-06: Right lower back strain (resolved)"
      ],
      "manager_quote": "He's feeling a little better. Right now we're in a good spot — we're just managing day-to-day.",
      "sources": ["Dodger Blue", "MLB Trade Rumors", "ESPN", "The Athletic", "MLB.com", "Dave Roberts press conference", "SI.com", "Sporting News"]
    },
    {
      "player": "Freddie Freeman",
      "team": "Los Angeles Dodgers",
      "position": "1B",
      "jersey": 5,
      "status": "active_healthy",
      "status_detail": "Active & healthy; chronic ankle managed via load management; all acute issues resolved; HBP wrist contusion (Jul 2025) fully resolved; neck stinger (Aug 2025) fully resolved",
      "current_injury": {
        "primary": "No acute injury",
        "chronic": "Left ankle (managed via load management); Right ankle (post debridement), quedan variables",
        "resolved": "Neck stinger (August 2025), Wrist contusion from HBP (July 2025), Rib/scar tissue (March 2025)",
        "mechanism": "Chronic ankle from prior sprains; resolved issues monitored for recurrence",
        "severity": "mild/moderate (chronic, managed)",
        "il_expected": false
       },
      "health_record": {
        "2026_update": "Wrist HBP (Brewers, 88 mph slip) — no fracture, played next game. Ankle swing adjustment optimized loading. Did not need IL or procedure per  Dr. Friedman.",
        "2025_update": "Neck stinger (Aug 27, vs Reds) resolved within days; rib/scar tissue Tokyo Dome cleared quickly; left ankle sprain managed",
        "2024_update": "Right ankle sprain + debridement Dec 2024 (played WS); fractured hamate (World Series); left thumb contusion; HBP wrist contusion",
        "latest_official_scans": "No fracture on wrist X-rays; neck stinger recurrence pattern identified but no structural damage"
      },
      "manager_quote": "He feels a lot better. There's still some kind of lingering effects, but nothing compromising.",
      "sources": ["MLB.com", "Dodger Blue", "USA Today", "Dave Roberts press conference", "LA Times", "CBS Sports", "Sportsnet (Canada team director)", "The Athletic (Fabian Ardaya)", "Forbes"]
    }
  ],
  "last_research_session": {
    "date": "2026-07-22",
    "researchers": ["community contributors", "primary source verification"],
    "methods": ["MLB.com official injury reports", "team press conferences", "beat reporter verification", "machine-readable structured format"]
  }
}
```