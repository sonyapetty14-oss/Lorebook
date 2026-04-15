# Lorebook Guide (GTA Universe)

This repository now includes an importable lorebook file:

- `GTA_Universe_Lorebook_120.json` (153 entries)

## Format
The JSON is structured for **SillyTavern-style lorebook/world-info imports**:

- Root object includes `name`, `description`, and `entries`.
- Each entry includes trigger keys (`key`, optional `keysecondary`), `comment`, and `content`.
- Operational fields are included for compatibility (e.g., `constant`, `order`, `position`, `disable`, `scanDepth`, `matchWholeWords`).

## Content Strategy
Entries are organized across:

1. Canon and tone anchor rules (constant entries).
2. Universe/game continuity entries (2D / 3D / HD).
3. Cities, districts, and regional context.
4. Factions and institutions.
5. Character references.
6. Radio/media and cultural atmosphere.
7. Criminal operation patterns.
8. Timeline enforcer checks.
9. Mission and narrative motifs.

## RP Usage Pattern
1. Import the JSON into your lorebook tool.
2. Keep canon-separation entries enabled as constants.
3. Trigger setting details using keys in prompts (e.g., `niko bellic`, `ballas hd`, `algonquin`, `timeline rule`).
4. For campaign consistency, lock one universe per story arc.

## Build Notes
This version was authored using a lorebook schema commonly used in the roleplay tooling ecosystem and populated with 100+ entries, as requested.
