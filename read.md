# Golden Square for Technical Consultations

Corporate website for **Golden Square** — technical consulting, media, procurement, energy, and smart-infrastructure solutions. Based in Amman, Jordan.

## Live site

- **Production:** https://goldensquare-jo.com/
- **Hosting:** ublac2 (WPMU DEV Unlimited)
- **Stack:** WordPress + Breakdance, UBLAC Admin UI Pro, UBLAC Fleet Agent

WordPress files and the database live on the server. This repo is for **project notes, exports, and agent workflows** — not a full WordPress mirror unless we add them later.

## Staging / legacy

- Earlier design exploration: https://goldensquare.ublac.site/ (ublac.site multisite)

## Local / agent access

### Breakdance MCP (Cursor Cloud Agents)

- **MCP name:** `goldensquare-jo-com-golden-square-wordpress`
- **Endpoint:** `https://goldensquare-jo.com/wp-json/mcp/mcp-adapter-default-server`
- **Type:** HTTP URL MCP (team dashboard — not `npx`)

Credentials are **not** stored in this repo. Team setup: Cursor Dashboard → Integrations & MCP.

### Fleet (CRM)

- **CRM:** https://crm.ublac.com
- Pairing token and `wp-config.php` constants are configured per environment (not in git).

## Server path (ublac2)

- Hub site slug: `golden`
- Path: `/home/sites/golden/public_html`

## Login

- WordPress admin uses the same **ublac** credentials as **base.ublac.co** (team password manager).

## Content sources

- Company profiles (PDF): corporate overview, services, partners, contact
- Partner logos: Al-Ghad, Al-Ahram, SANEX, Sellier & Bellot, Wtorplast, SVOS, OTAVAN, BRESSON

## What belongs in this repo (optional)

- `docs/` — briefs, copy, launch checklists
- `exports/` — Breakdance or content exports when needed
- `.cursor/` — environment notes for Cloud Agents (no secrets)

## Do not commit

- SSH keys, application passwords, Fleet pairing tokens, SQL dumps, `wp-config.php`

## UBlac

Built and maintained by [UBlac](https://ublac.co).
