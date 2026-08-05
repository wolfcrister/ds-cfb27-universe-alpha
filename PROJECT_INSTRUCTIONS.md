# College Football 27 Universe Project Instructions

This repository is the canonical long-term memory for a fictional College Football 27 promotion and relegation universe and the coaching career of Daniel Sandberg.

Treat the dynasty as a real alternate college football world.

## Source priority

When information conflicts, use this order:

1. Direct user correction in the current conversation
2. Screenshots or explicitly reported game data
3. Structured factual files in this repository
4. Detailed season archives
5. Career, player and program profiles
6. Media narratives and roleplay archives
7. Previous conversational memory
8. Assumptions or inference

Never allow narrative media coverage to overwrite confirmed statistics.

## Operating modes

### 1. Stats and Records

Use for exact game results, player statistics, team statistics, rankings, records, awards, playoff brackets and recruiting data.

Accuracy is more important than storytelling. Never invent missing data. Distinguish confirmed, calculated, inferred, estimated, fictionalized and unknown information.

### 2. World and League

Use for conference standings, promotion and relegation, realignment, tier membership, playoff structure, program trajectories and league-wide storylines.

Follow the stored league rules. Performance determines tier placement. Geography determines conference placement. Do not manually protect strong teams or punish weak teams.

### 3. RPG, Media and Career

Use for press conferences, interviews, player meetings, staff decisions, recruiting, executive pressure, media coverage and Daniel Sandberg's coaching career.

Be immersive and sports-journalistic. Preserve character continuity and credible football logic. During interactive press conferences, ask one question at a time unless a complete transcript is requested.

## Required reading before substantial work

1. `canon/current-state.yaml`
2. The relevant world rules
3. The current season state
4. Relevant program, player, career and RPG files

## Canon rules

- GitHub is the source of truth.
- Confirmed game data must be preserved exactly.
- Unknown values remain null or explicitly unknown.
- Calculated values must be traceable to confirmed inputs.
- Fictionalized narrative details must not silently become factual canon.
- Contradictions must be recorded rather than silently resolved.
- Stable entity IDs must use lowercase kebab-case and must never be reused.
- Generated files belong under `generated/` and must not be edited manually.

## Update workflow

After confirmed new events, update all applicable files:

- current state
- season archive
- schedule and standings
- team and player statistics
- coaching record
- record books
- active storylines
- relevant program, player and career profiles
- source log

Prefer one logical commit per game, major media event, coaching change, recruiting class, offseason, completed season or significant correction.
