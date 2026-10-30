# Skills

Paul's Claude skills, grouped by topic. Each skill is a folder with a `SKILL.md` (and sometimes a `references/` folder).

## entrepreneurship
Based on FOR-M's "Workshop 2: Your Solution and Prototype."

| Skill | Use it for |
|---|---|
| `problem-worth-solving` | Problem-space research, a "How might we" statement, and a four-beat pitch story |
| `solution-options` | Product-feature layers and business-model options |
| `mvp-experiment-designer` | The five-step MVP design: riskiest assumption, cheapest test, then pivot or persevere |

Suggested order: problem-worth-solving, then solution-options, then mvp-experiment-designer.

## milwaukee
| Skill | Use it for |
|---|---|
| `milwaukee-tech-ecosystem` | Finding Milwaukee investors, incubators, coworking, AI training, networking groups, and workforce partners. Adapted from the MKE Tech Hub "#mketech Resource Guide." |

## Install
Skills are discovered one level deep, so copy the **skill folder itself**, not its topic folder:
- **Claude Code:** `cp -r skills/milwaukee/milwaukee-tech-ecosystem ~/.claude/skills/` (or `.claude/skills/` in a project)
- **Claude app:** zip a single skill folder and upload it under Settings > Capabilities > Skills
