# Personal AI Skill System

A long-term, ChatGPT-first AI operating system for research, e-commerce, organic marketing, AI video production, technical work, and multi-session projects.

## Start here
1. Read [ChatGPT Setup](CHATGPT_SETUP.md).
2. Copy [Project Instructions](CHATGPT_PROJECT_INSTRUCTIONS.md) into your ChatGPT Project instructions.
3. Add [Core Rules](CORE/CORE_RULES.md), [Skill Router](ROUTER/ALL_SKILLS.md), and [Work Profile](USER_WORK_PROFILE.md) as Project sources.
4. Add only the specialist skills relevant to that Project.
5. Use [Project State Template](PROJECTS/PROJECT_STATE_TEMPLATE.md) to preserve decisions, metrics, blockers, and next actions.

## Important limitation
This repository is the version-controlled source of truth; it does not train a model or automatically install Skills into ChatGPT. ChatGPT must be given the relevant instructions and source files through a Project or another supported integration. A GitHub repository connection does not, by itself, guarantee that every Skill is automatically loaded.

## Architecture
- CORE: truth, priorities, approval gates, and execution standards.
- USER_WORK_PROFILE: stable, work-relevant preferences only.
- ROUTER: selects the smallest relevant skill set.
- SKILLS: focused specialist workflows.
- PROJECTS: checkpoints and persistent project state.
- TEMPLATES: repeatable briefs and scorecards.
- EVALUATION: benchmark cases and outcome tracking.

## Operating principles
Evidence before confidence. Speed for low-risk tasks; deeper research for consequential decisions. Execute reversible work autonomously; request approval for material commitments. Test new knowledge before turning it into a Skill. Measure time saved, errors avoided, rework, and real-world outcomes—not system complexity.

See [Changelog](CHANGELOG.md) for revisions.
