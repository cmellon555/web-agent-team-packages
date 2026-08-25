# Gemini Web Agent Team (Antigravity / Gemini CLI)

15 specialist skills for Google Antigravity and Gemini CLI. Drop into `.agents/skills/` or `~/.gemini/antigravity-cli/skills/`. Invoke as `/<skill-name>`.

## The Team
| Skill | Role |
|-------|------|
| gemini-design-orchestrator | Conductor |
| gemini-project-architect | Sitemap & structure |
| gemini-cro-wireframe-strategist | Conversion + wireframes |
| gemini-art-director | Visual direction |
| gemini-copywriter | Conversion copy |
| gemini-image-director | Image prompts |
| gemini-web-design | Builds pages |
| gemini-design-qa-critic | QA & critique |
| gemini-seo-aeo-optimizer | SEO + AEO |
| gemini-deploy-coordinator | Ships (Vercel/Cloudflare/Firebase) |
| gemini-shopify-theme-builder | Shopify Liquid |
| gemini-cloudflare-dns | DNS & Pages |
| gemini-antigravity-prompting | Writes Antigravity task specs |
| gemini-churchclip-ai | ChurchClip AI specialist |
| gemini-bible-study-sheet | Bible Study Sheet specialist |

## Recommended flow
1. `/gemini-design-orchestrator` with your brief
2. It routes architect → art → copy → images → build → SEO → QA → deploy

## Keys & limits
- **Vercel / Cloudflare / Shopify / Firebase**: real third-party services. You supply your own tokens. The deploy skill checks env vars and tells you exactly what's missing.
- **Gemini / Antigravity**: native. Pricing follows Gemini token usage (pay-as-you-go). Antigravity is included in eligible Gemini Enterprise plans.
- **Cloudflare script**: placeholder token — replace with your own `CLOUDFLARE_API_TOKEN`.

## ChurchClip AI & Bible Study Sheet
Two dedicated specialists included. Point the orchestrator at either.

## Install
```
cp -r gemini-web-agent-team/* .agents/skills/
# or
cp -r gemini-web-agent-team/* ~/.gemini/antigravity-cli/skills/
```
