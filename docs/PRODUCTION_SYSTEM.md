# EJJoftheCloud Production System v1.0

## Purpose
This is the official operating system for every EJJoftheCloud lesson. The goal is to make learning, building, proving, documenting, publishing, tracking, and career evidence one connected process rather than a collection of standalone tasks.

## Core Principle
We do not create content and then document the work. Creating, building, proving, documenting, and publishing are one process.

## System Roles
- **Google Drive:** content production, archive, social assets, captions, scripts, approved graphics, and published assets.
- **GitHub:** technical knowledge base, proof of work, labs, code, architecture, troubleshooting, reusable learning record, and long-term career portfolio.
- **Master Curriculum Tracker:** source of truth for Day number, topic, season, objective, status, cost, links, and progression.

## Day Closeout Pipeline
A Day is not complete until all required steps for that lesson type are complete.

1. Mission selection from the 365 tracker.
2. Canonical learning package and authoritative sources.
3. Social content package: carousel, ZIP, Reel assets, and posting-copy document.
4. Drive storage in one Day folder.
5. GitHub knowledge package with `README.md` and `day.yaml`.
6. Lab/code artifacts when applicable.
7. Proof of Work when applicable.
8. Architecture documentation when applicable.
9. Troubleshooting documentation when applicable.
10. Skills and certification mapping.
11. Azure cost and XP metadata.
12. GitHub commit.
13. Tracker closeout.
14. Publishing and URL capture.
15. Later analytics update.
16. Weekly recap and career-evidence feeds.

## GitHub Minimum Standard
Every lesson gets at minimum:

```text
DayXXX-Topic/
├── README.md
└── day.yaml
```

Only add folders when they are actually needed:

```text
lab/
cli/
powershell/
terraform/
scripts/
architecture/
screenshots/
logs/
troubleshooting/
proof/
```

Never create empty filler folders.

## README Standard
Every Day README should use the following structure where applicable:

1. Day + Topic
2. Mission Metadata
3. Objective
4. What Is It?
5. Simple Explanation
6. Why It Matters
7. Key Concepts
8. Real-World Example
9. Azure / Cloud Example
10. What I Learned
11. What Confused Me
12. What Finally Clicked
13. Lab
14. Commands
15. Architecture
16. Proof of Work
17. Troubleshooting / Mistakes
18. Cost
19. Authoritative Resources
20. Skills Demonstrated
21. Certification Alignment
22. Next Mission

## Proof of Work Standard
Technical lessons should preserve evidence when applicable, including deployment success screenshots, portal configuration screenshots, CLI output, Terraform plan/apply output, connectivity tests, validation results, and logs.

Concept-only lessons do not need fake proof artifacts.

## Architecture Standard
For meaningful design decisions, include an architecture diagram and a `decisions.md` file recording:
- Decision
- Why
- Alternatives considered
- Why alternatives were rejected

## Troubleshooting Standard
When something fails, document:
- Problem
- Expected behavior
- Observed behavior
- Symptoms
- Initial hypothesis
- Investigation
- Root cause
- Fix
- Validation
- What I learned

## Authoritative Resources
Prefer official documentation such as Microsoft Learn, Azure documentation, Terraform documentation, RFCs, Kubernetes documentation, GitHub documentation, NIST, and vendor documentation.

## Skills and Certification Mapping
Each `day.yaml` should map relevant skills, Azure services, tools, competencies, and certification alignment. This data will support future skills indexes, certification indexes, portfolio navigation, resume evidence, and interview preparation.

## Cost, XP, and Rank
Each Day records its own XP and Azure cost. Aggregate XP, rank, season XP, lifetime Azure cost, lab count, project count, and Boss Battle count should be calculated from Day metadata instead of manually duplicated.

## Completion States
- **Production Complete:** required learning, social package, Drive storage, GitHub package, proof/code if required, and tracker closeout are complete.
- **Published:** content is live and URLs are recorded.
- **Analytics Updated:** performance metrics have been recorded later.

## Permanent Rule
**Social media tells the story. GitHub proves the work. Drive preserves the production system. The tracker connects everything.**

## Workflow Summary
MISSION SELECTED → Learn / research → Canonical lesson → Carousel → Reel → Posting-copy document → ZIP and Drive → GitHub README + day.yaml → Lab/code → Proof of Work → Architecture → Troubleshooting → Resources → Skills → Certification alignment → Cost → Commit → Index update → Tracker closeout → Publish → URLs → Analytics later → Weekly recap → Career/interview evidence → MISSION COMPLETE
