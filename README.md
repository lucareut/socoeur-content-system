# Socoeur — Content System

This repository is the structured content system for Socoeur.

It centralizes the strategic and operational foundations of the brand's social media and content production. It does not store visual assets (photos, videos, design files). Instead, it contains the structural layer that ensures coherence, scalability, and long-term brand consistency.

This repository functions as the strategic brain of the content operation.

---

## Purpose

The goal of this system is to:

- Maintain strong visual and editorial consistency
- Structure AI-assisted content generation intelligently
- Keep production lean and agile
- Separate strategy from execution
- Protect long-term brand positioning
- Enable scalable content operations across collections

This system is designed to support the World Cup 2026 chapter and future brand evolutions.

---

## Central Reference

**`CONTEXT.md`** at the root of this repository is the single source of truth for all AI content generation.

It contains:
- Brand positioning
- Tone of voice
- Visual philosophy
- Caption structure
- Sprint structure
- Format definitions
- Content objective

All AI-generated content must reference `CONTEXT.md` before generating.

---

## Repository Structure

```
socoeur-content-system/
├── CONTEXT.md                        ← Central brand + AI reference
├── README.md
├── docs/
│   ├── content_plan.md               ← Full content plan (World Cup 2026)
│   ├── brand_guidelines.md           ← Visual identity rules
│   └── social_media_charter.md       ← Editorial charter
├── prompts/
│   ├── format_symbolic_tease.md
│   ├── format_urban_presence.md
│   ├── format_material_focus.md
│   ├── format_controlled_motion.md
│   ├── brand_core_prompt.md
│   └── trend_research_prompt.md
├── sprints/
│   ├── sprint_1.md                   ← Cultural Tease (mid-March → early April)
│   ├── sprint_2.md                   ← Fragment Reveal
│   ├── sprint_3.md                   ← Official Drop
│   └── sprint_4.md                   ← Tournament Mode
└── automation/
    ├── n8n_workflows.json
    └── script_generation_prompt.md
```

---

## Workflow

Strategy lives in this repository.

Execution is tracked in the operational Google Sheet: **Socoeur_Content_OS**

Each content piece moves through:

```
Idea → Scripted → Ready to Shoot → Shot → Edited → Ready → Published
```

---

## Tools

This repository is actively maintained using **Claude Code** as the primary working tool.

Claude Code is used to:
- Generate and refine content prompts
- Maintain system documentation
- Structure sprint planning
- Ensure consistency across all files

AI is not used to define strategy.
Creative direction remains human-led.

---

## Operating Principles

Consistency over volume.
Clarity over complexity.
Structure over improvisation.
Automation only where it adds real value.
Creativity remains human-led.

This system is designed to evolve without compromising identity.
