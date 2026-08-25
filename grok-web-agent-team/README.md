# Grok Web Agent Team

15 specialist skills for Grok Build. Drop into `~/.grok/skills/` or `./.grok/skills/`. Invoke with `/grok-...`.

## The Team
| Skill | Role |
|-------|------|
| grok-design-orchestrator | Conductor — plans & delegates |
| grok-project-architect | Sitemap & structure |
| grok-cro-wireframe-strategist | Conversion + wireframes |
| grok-art-director | Visual direction & tokens |
| grok-copywriter | Conversion copy |
| grok-image-director | Image prompts (Grok Imagine) |
| grok-web-design | Builds the pages |
| grok-design-qa-critic | QA & critique |
| grok-seo-aeo-optimizer | SEO + Answer Engine |
| grok-deploy-coordinator | Ships to Vercel/Cloudflare |
| grok-shopify-theme-builder | Shopify Liquid |
| grok-cloudflare-dns | DNS & Pages |
| grok-build-prompting | Writes Grok Build task specs |
| grok-churchclip-ai | ChurchClip AI specialist |
| grok-bible-study-sheet | Bible Study Sheet specialist |

## Recommended flow
1. `/grok-design-orchestrator` with your brief
2. It routes to architect → art → copy → images → build → SEO → QA → deploy

## Keys & limits
- **Vercel / Cloudflare / Shopify**: real third-party services. You need your own accounts + tokens. The deploy skill checks for env vars and tells you exactly what's missing — it never invents keys.
- **Grok Build / Grok Imagine**: native to your Grok environment. Free tier has limits; SuperGrok raises caps.
- **Cloudflare script**: ships with a placeholder token. Replace with your own `CLOUDFLARE_API_TOKEN`.

## ChurchClip AI & Bible Study Sheet
Two dedicated specialists are included. Point the orchestrator at either and it loads the matching brief.

## Install
```
cp -r grok-web-agent-team/* ~/.grok/skills/
```
Then in Grok Build: `/grok-design-orchestrator build me a landing page for <thing>`.
