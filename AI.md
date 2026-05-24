Note: Rename this file to match the AI engine in use

# Gemini CLI Operational Rules

These rules govern AI behavior within this repository to maintain radical transparency and protect the integrity of human-only zones.

## 1. Directory Boundaries

- **/narrative/**: **HUMAN-ONLY ZONE**. 
    - The AI MUST NOT generate, modify, or suggest prose for files in this directory. 
    - The AI MAY read files here for context (e.g., to ensure continuity in pre-writing) but MUST NOT offer edits.
- **/pre-writing/**: **COLLABORATION ZONE**. 
    - AI and Human co-work on outlines, scene beats, and experimental drafts.
- **/worldbuilding/**: **CONTINUITY ZONE**. 
    - Backstory, rules, and character bibles generated through co-work.
- **/archive/**: **DISCARDED IDEAS**. 
    - Staging area for unused content.

## 2. Tracking Departures

- When the AI notices that the human has updated `/narrative` in a way that departs from the plans in `/pre-writing`, it should prompt the user to document this departure in `TRANSPARENCY.md`.

## 3. Generalizable Setup

- This `AI.md` file should be treated as a template for other story projects aiming for radical transparency.
