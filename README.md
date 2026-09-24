# C524 Certified Lean Six Sigma Yellow Belt (CLSSYB)

Complete courseware for the Tertiary Infotech Academy **Certified Lean Six Sigma Yellow Belt** short course — a 2-day, hands-on programme that follows the DMAIC roadmap end to end using one continuous scenario, the **Contoso Service Desk**.

This is a **non-WSQ commercial short course**: there is no assessment, no SSG/SkillsFuture funding component and no attendance-tracking requirement. Learning is reinforced through hands-on labs, each with its own verification step.

## Course Information

- **Course Code:** C524
- **Course Title:** Certified Lean Six Sigma Yellow Belt (CLSSYB)
- **Duration:** 2 days · 7.5 instructional hours per day (15 hours)
- **Daily Timing:** 9:30 am – 5:30 pm (30-minute lunch break)
- **Level:** Beginner
- **Mode:** Instructor-led, hands-on Lean Six Sigma labs
- **Version:** v1 · 23 September 2026
- **Trainer:** Dr. Alfred Ang
- **Course Registration:** [Certified Lean Six Sigma Yellow Belt (CLSSYB)](https://www.tertiarycourses.com.sg/certified-lean-six-sigma-yellow-belt.html)
- **Reference:** The Council for Six Sigma Certification (CSSC), *Six Sigma: A Complete Step-by-Step Guide*

## Learning Outcomes

1. Define a project and establish the scope of work using Six Sigma's Define, Measure and Analyse phases.
2. Apply Lean and Six Sigma concepts — value, waste, defects and variation — to a work process.
3. Map a process using SIPOC, process maps and value stream maps to expose handoffs and waste.
4. Collect and analyse process data using check sheets, Pareto charts, run charts and basic metrics.
5. Identify root causes using 5 Whys, Fishbone analysis and evidence-based prioritisation.
6. Recommend improvement and control actions to sustain gains, and continue your Lean Six Sigma development.

## Course Structure — the DMAIC roadmap

| # | Topic | Coverage | Labs |
|---|-------|----------|------|
| 1 | Six Sigma Foundations | 15% | 1 |
| 2 | Define — Scope the Problem | 25% | 2–5, 11 |
| 3 | Measure — Quantify Performance | 25% | 6, 12 |
| 4 | Analyze — Find the Root Cause | 20% | 7, 8 |
| 5 | Improve — Fix the Cause | 10% | 9, 13 |
| 6 | Control — Hold the Gain | 5% | 10, 14 |

## Activities

Every activity builds on the same Contoso Service Desk scenario, so outputs accumulate into one complete improvement package.

| # | Activity | DMAIC phase | Type |
|---|-----|-------------|------|
| 1 | [Yellow Belt Role, Certification Paths, and Improvement Scenario](activities/01%20-%20Yellow%20Belt%20Role%2C%20Certification%20Paths%2C%20and%20Improvement%20Scenario) | FOUNDATIONS | Core |
| 2 | [Lean, Six Sigma, Waste, Voice of Customer, and Value](activities/02%20-%20Lean%2C%20Six%20Sigma%2C%20Waste%2C%20Voice%20of%20Customer%2C%20and%20Value) | DEFINE | Core |
| 3 | [SIPOC, Process Mapping, Handoffs, and SME Support](activities/03%20-%20SIPOC%2C%20Process%20Mapping%2C%20Handoffs%2C%20and%20SME%20Support) | DEFINE | Core |
| 4 | [PDCA Small Improvement Project Charter](activities/04%20-%20PDCA%20Small%20Improvement%20Project%20Charter) | DEFINE | Elective |
| 5 | [DMAIC Overview, Problem Statement, Scope, and Stakeholders](activities/05%20-%20DMAIC%20Overview%2C%20Problem%20Statement%2C%20Scope%2C%20and%20Stakeholders) | DEFINE | Core |
| 6 | [Data Collection, KPIs, Check Sheets, and Basic Metrics](activities/06%20-%20Data%20Collection%2C%20KPIs%2C%20Check%20Sheets%2C%20and%20Basic%20Metrics) | MEASURE | Core |
| 7 | [Pareto, Run Charts, Variation, Yield, DPU, and DPMO](activities/07%20-%20Pareto%2C%20Run%20Charts%2C%20Variation%2C%20Yield%2C%20DPU%2C%20and%20DPMO) | ANALYZE | Core |
| 8 | [Root Cause Analysis with 5 Whys, Fishbone, and Evidence](activities/08%20-%20Root%20Cause%20Analysis%20with%205%20Whys%2C%20Fishbone%2C%20and%20Evidence) | ANALYZE | Core |
| 9 | [Countermeasures, 5S, Mistake Proofing, Standard Work, and Kaizen](activities/09%20-%20Countermeasures%2C%205S%2C%20Mistake%20Proofing%2C%20Standard%20Work%2C%20and%20Kaizen) | IMPROVE | Core |
| 10 | [Control Plan, A3 Summary, Handover, and Certification Readiness](activities/10%20-%20Control%20Plan%2C%20A3%20Summary%2C%20Handover%2C%20and%20Certification%20Readiness) | CONTROL | Core |
| 11 | [Affinity Diagram and Kano Analysis](activities/11%20-%20Affinity%20Diagram%20and%20Kano%20Analysis) | DEFINE | Elective |
| 12 | [Value Stream Map and Takt Time](activities/12%20-%20Value%20Stream%20Map%20and%20Takt%20Time) | MEASURE | Elective |
| 13 | [Solution Selection Matrix, Benchmarking, and FMEA](activities/13%20-%20Solution%20Selection%20Matrix%2C%20Benchmarking%2C%20and%20FMEA) | IMPROVE | Elective |
| 14 | [Descriptive Statistics and Implementation Planning](activities/14%20-%20Descriptive%20Statistics%20and%20Implementation%20Planning) | CONTROL | Elective |

See [activities/tools.md](activities/tools.md) for the browser-based problem-solving tools, and
[activities/README.md](activities/README.md) for the shared Contoso data set.

Each activity folder is self-contained: a **Facilitator Guide**, a **Learner Worksheet** and a
**Checklist** (DOCX + PDF), plus `data/` (the mock CSVs analysed), `templates/` (blank worksheets)
and, for Activity 7, `solution/` (worked answers — trainer only).

## Repository Structure

```
.
├── courseware/                     Learner-facing artifacts
│   ├── *-v1.pptx / *-v1.pdf        Slide deck (262 slides, all-white house style)
│   ├── LP-*.docx / LP-*.pdf        Lesson Plan
│   ├── LG-*.docx / LG-*.pdf        Learner Guide
│   ├── assets/                     Images used by the deck
│   └── archive/                    Superseded versions (kept locally, not pushed)
├── activities/                     14 self-contained activity packs
│   └── NN - <title>/               Facilitator Guide + Learner Worksheet + Checklist
│                                   (DOCX+PDF) + data/ + templates/ [+ solution/]
├── LG-*.md                         Learner Guide Markdown mirror
└── .claude/
    ├── skills/                     Build pipeline, QA scanner, lab standard, Drive push
    └── commands/                   /gdrive-push-nonwsq + /lms-push-nonwsq
```

## Provenance

This courseware is a **direct conversion of the WSQ counterpart course**
(`TGS-2025053922 — Certified Lean Six Sigma Yellow Belt (CLSSYB) Training`, v9), produced with
the `wsq-to-non-wsq` skill. The deck, Lesson Plan, Learner Guide and all 14 activity packs are the
WSQ artifacts with the WSQ layer removed and the schedule retimed to the non-WSQ day —
same topic spine, same activities, same house design.

Removed in conversion: digital attendance, the WSQ Skills Framework / TSC alignment, the
Learning Outcomes slide, assessment briefing / assessment / assessment-flow slides, the
TRAQOM survey (rewritten in place as **Course Feedback**), and the SkillsFuture SOA and
75%-attendance funding wording.

Retimed: 9:30 am – 5:30 pm, **450 instructional minutes per day** plus a single 30-minute
lunch (the WSQ parent's 9:30–6:30 day with a 1-hour lunch and two tea breaks does not
apply). Day 2's freed assessment block was redistributed proportionally across every
topic rather than absorbed by one.

### Quality check

```bash
python3 .claude/skills/non-wsq-courseware-qa/scan_prohibited.py .
```

Scans every generated artifact for content that must not appear in a non-WSQ course —
WSQ/SSG/SkillsFuture/TRAQOM references, digital attendance, course-funding language, TGS
course codes and any formal-assessment material — and reports each hit with its exact slide,
paragraph or line number.

### Publishing to Google Drive

```bash
python3 .claude/skills/gdrive-push-nonwsq/gdrive_push_nonwsq.py "<drive-folder-link>" --dry-run
python3 .claude/skills/gdrive-push-nonwsq/gdrive_push_nonwsq.py "<drive-folder-link>"
```

Routes each artifact to its Drive folder — deck PPT → **Trainer Slides**, deck PDF →
**Learner Slides**, LG → **Learner Guide**, LP → **Lesson Plan**, `activities/` → **Activities** —
auto-creating each folder's `archive/` and moving superseded versions into it. Nothing on
Drive is ever deleted, and unchanged files (matched by MD5) are skipped.

Activities is **additive**: lab files are uploaded and updated while the trainer's existing
datasets and `.xlsx` templates are left in place. Pass `--mirror` to make it match `activities/`
exactly. Requires `rclone` (`rclone config create gdrive drive scope=drive`).

### Publishing the links to the course page

```bash
export TC_API_KEY='<storefront X-API-Key>'
python3 .claude/skills/lms-push-nonwsq/lms_push_nonwsq.py --sku C524 --dry-run
python3 .claude/skills/lms-push-nonwsq/lms_push_nonwsq.py --sku C524
```

Reads the Drive links and writes them onto the course record in the
tertiarycourses.com.sg admin — Trainer Slides (PPT), Learner Slides (PPT PDF), Lesson
Plan, Learner Guide, and Lab URL (the Activities **folder**). Only changed fields are
written. The Drive folder is discovered from the course's Courseware Link, so the SKU
alone is enough after one Drive push.

## Included Skills

The `.claude/skills/` folder carries the reusable non-WSQ courseware toolchain:

| Skill | Purpose |
|-------|---------|
| `non-wsq-courseware-build` | Single-source pipeline generating the PPT, Lesson Plan and Learner Guide |
| `non-wsq-courseware-qa` | Prohibited-content scanner + completeness, alignment and visual checks |
| `non-wsq-lab-author` | Authoring standard for connected, self-verifying hands-on labs |
| `gdrive-push-nonwsq` | Publishes the built courseware to the course's Google Drive folder |
| `lms-push-nonwsq` | Writes the Drive links onto the course record at tertiarycourses.com.sg |

`.claude/commands/` exposes the last two as the `/gdrive-push-nonwsq` and
`/lms-push-nonwsq` slash commands. The full publish flow is: build → QA →
`/gdrive-push-nonwsq` → `/lms-push-nonwsq`.

---

© 2026 Tertiary Infotech Academy Pte Ltd (UEN 201200696W). All rights reserved.
[www.tertiarycourses.com.sg](https://www.tertiarycourses.com.sg)
