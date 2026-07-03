# Novel Writing Automation System — User Guide

## Overview

This is a complete web novel writing workflow system designed for the long-form serialization of *"The Abstract Programmer and the Abstract System Brave the Web Novel World"*. The system consists of 5 creation phases, 9 skill modules, and a 7-step loop workflow, covering the entire pipeline from outline design to final draft backup.

## Directory Structure

```
novel-project/
├── outline_and_chapter/    ← Full novel outline + chapter templates
│   ├── full_outline.md
│   └── chapter_template.md
├── manuscripts/            ← Chapter TXT files, named by "chapter_no + title"
│   └── naming_convention.md
├── world_building/         ← Characters / World / Timeline / Foreshadowing
│   ├── characters.md
│   ├── world_setting.md
│   ├── timeline.md
│   └── foreshadowing_tracker.md
├── skill_configs/          ← 1 main skill + 7 sub-skills + 1 automation skill
│   ├── main_skill-chapter_full_pipeline.md
│   ├── sub1-data_organization.md
│   ├── sub2-chapter_plotting.md
│   ├── sub3-platform_standard_writing.md
│   ├── sub5-content_polishing.md
│   ├── sub6-storyline_update.md
│   ├── sub7-auto_backup.md
│   └── automation-daily_backup_and_review.md
├── backups/                ← Version history + backup archives
│   └── version_history.md
└── user_guide_EN.md        ← This file
```

## Five Phases

### Phase 1: Workspace Initialization
Create the five folders, define their responsibilities, and establish the project skeleton.

### Phase 2: Skill System Setup
Build 1 main skill + 7 sub-skills + 1 automation skill, each with clear input/output boundaries and execution steps.

### Phase 3: Pre-Writing Preparation
Complete world-building, character design, main plot outline, and writing style establishment.

### Phase 4: Standardized Chapter Writing
Follow the 7-step loop for each chapter, completing the full creative pipeline per chapter.

### Phase 5: Review and Revision
Every 5 chapters undergo a systematic review by AI for logical consistency, foreshadowing recovery, and writing quality.

## The 7-Step Loop (Per Chapter)

| Step | Action | Skill Used | Output |
|------|--------|-----------|--------|
| 1 | Data Organization | Data & Previous Context | Status report |
| 2 | Plot Planning | Chapter Plotting | Chapter scenario plan |
| 3 | Writing | Platform Standard Writing | First draft |
| 4 | Compliance Check | Compliance & Consistency | Review report |
| 5 | Content Polishing | Content Optimization | Polished draft |
| 6 | Storyline Update | Storyline & Character Update | Updated tracking docs |
| 7 | Auto Backup | Auto Version Backup | Version archive |

## Core Setting

- **Title:** *The Abstract Programmer and the Abstract System Brave the Web Novel World*
- **Protagonist:** He Yiwei — an anti-stereotype abstract programmer
- **System:** Abstract System — a chaotic, trolly AI co-protagonist
- **Worldview:** Server Universe (stars = author IDs, planets = web novel worlds)
- **Core Mechanic:** Random planet-hopping each chapter; move to the next upon completing the main quest
- **Goal:** Find a way home
- **Element Mix:** 50% tech (He Yiwei's own) + 50% random (Abstract System's tampering)
- **Hard Rules:** No character-breaking / He Yiwei must not resent the Abstract System

## Skill List

### Main Skill
**Full Chapter Pipeline** — Orchestrates all 7 sub-skills to complete the full pipeline from data to final draft.

### Sub-Skills
| No. | Name | Responsibility |
|-----|------|---------------|
| 1 | Data & Previous Context | Read character status, previous summary, unresolved foreshadowing |
| 2 | Chapter Plotting | Plan 3-5 core events, determine conflict and pacing |
| 3 | Platform Standard Writing | Generate first draft per platform style |
| 4 | Compliance & Consistency | Check for OOC, plot contradictions, policy violations |
| 5 | Content Optimization | Polish dialogue, visual imagery, pacing |
| 6 | Storyline & Character Update | Update character status, foreshadowing, chapter summary |
| 7 | Auto Version Backup | Archive chapter text + metadata to version directory |

### Automation Skill
**Daily Backup & Compliance Scan** — Scheduled daily auto-backup + sensitive word scanning.

## How to Use

1. Ensure the working directory is the project root
2. Invoke the main skill "Full Chapter Pipeline" to start the writing process
3. The main skill will automatically invoke sub-skills in order following the 7-step loop
4. Each step displays a progress indicator (e.g., 【Step 1/7 — Data Organization】)
5. If compliance issues are found, the workflow loops back for correction
6. Each completed chapter is automatically backed up with full version history
