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

### entrepreneurship/hormozi
Offer-design skills based on Alex Hormozi's *$100M Offers*, written in my own words.

| Skill | Use it for |
|---|---|
| `market-check` | Checking whether a market is worth selling to (pain, purchasing power, easy to reach, growing) and narrowing to a niche |
| `grand-slam-offer-builder` | Building an offer from every customer obstacle, then trimming and stacking it |
| `value-equation-audit` | Scoring an offer on dream outcome, likelihood, time delay, and effort, and finding the lever to pull first |
| `offer-enhancers` | Scarcity, urgency, bonuses, guarantees, and naming |

Suggested order: market-check, then grand-slam-offer-builder, then offer-enhancers, then value-equation-audit. The audit also works on its own for an existing offer. These fit after `solution-options` (who pays) and before `mvp-experiment-designer` (test it).

Other Hormozi skills worth a look:
- [zacker-tech/hormozi-skills](https://github.com/zacker-tech/hormozi-skills): 10 skills covering *$100M Offers*, *$100M Leads*, and *$100M Money Models*
- [alex-hormozi-pitch](https://github.com/microck/ordinary-claude-skills): interactive `/create-hormozi-pitch` offer builder (in microck/ordinary-claude-skills)

## milwaukee
| Skill | Use it for |
|---|---|
| `milwaukee-tech-ecosystem` | Finding Milwaukee investors, incubators, coworking, AI training, networking groups, and workforce partners. Adapted from the MKE Tech Hub "#mketech Resource Guide." |

## Install
Skills are discovered one level deep, so copy the **skill folder itself**, not its topic folder:
- **Claude Code:** `cp -r skills/milwaukee/milwaukee-tech-ecosystem ~/.claude/skills/` (or `.claude/skills/` in a project)
- **Claude app:** zip a single skill folder and upload it under Settings > Capabilities > Skills
