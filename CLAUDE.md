# CLAUDE.md — TheArea

## Before Writing Any Code

1. Read `RESEARCH.md` in full — it contains competitor analysis, market sizing, consumer trends, monetization models, and gap analysis. This is your strategic foundation.
2. Create `PRD.md` at the root of this repo before touching any code. Get confirmation before proceeding.

## PRD.md Must Include

- **Vision** — what TheArea is and what it is not (not a recovery app, not a fitness app)
- **Target user** — sober-curious 21-35, Gen Z-native, lifestyle-focused
- **Core features** — prioritized list with brief descriptions
- **Screens / navigation structure** — all major screens listed
- **Data models** — key entities and relationships
- **Monetization** — freemium tier, premium, brand partnerships, events
- **Out of scope (v1)** — what we're explicitly not building yet
- **Success metrics** — how we know it's working

## Stack

- Expo (React Native, TypeScript)
- Target: iOS first (Xcode), Android later
- No web build required

## Design Principles

- Aspirational, not clinical
- Nightlife energy, zero alcohol
- Never use recovery language, streak mechanics, or fitness-only framing
- Dark UI, bold typography, high contrast
- The vibe: "going out" but constructive

## Workflow

1. Read RESEARCH.md
2. Write PRD.md → wait for approval
3. Scaffold features one screen at a time
4. Commit after each working screen
