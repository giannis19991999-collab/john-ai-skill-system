# ChatGPT Setup Guide

## Recommended setup
Create a ChatGPT Project named **Personal AI Skill System**, or create focused Projects for E-commerce, AI Video, Marketing, and Shopify.

### Project instructions
Copy [CHATGPT_PROJECT_INSTRUCTIONS.md](CHATGPT_PROJECT_INSTRUCTIONS.md) into the Project instructions field.

### Project sources
Start with:
- [CORE/CORE_RULES.md](CORE/CORE_RULES.md)
- [ROUTER/ALL_SKILLS.md](ROUTER/ALL_SKILLS.md)

Then add only the relevant specialist skills:
- Product evaluation: `SKILLS/business/product-research/SKILL.md` and `unit-economics/SKILL.md`
- Organic content: `SKILLS/marketing/organic-content/SKILL.md`
- Cinematic showcases: `SKILLS/creative/cinematic-video/SKILL.md`
- Shopify: `SKILLS/technical/shopify-liquid/SKILL.md`
- Research: `SKILLS/research/deep-research/SKILL.md` and `claim-verification/SKILL.md`

## Limitations
A GitHub repository is not automatic ChatGPT memory. Uploading a Markdown skill as a Project source does not make it a native installed Skill. Project instructions guide behavior only when the relevant files are available to the conversation. Do not upload passwords, API keys, payment data, or sensitive customer information.

## Workflow
1. Define the outcome and constraints.
2. Let the router identify the smallest useful skill set.
3. Execute the workflow and verify important claims.
4. At the end of substantial work, save a checkpoint using `PROJECTS/PROJECT_STATE_TEMPLATE.md`.
