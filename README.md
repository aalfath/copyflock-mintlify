# CopyFlock docs

Customer-facing help center for [CopyFlock](https://copyflock.com), the cloud futures trade copier. Built with [Mintlify](https://mintlify.com).

## Structure

| Folder | Content |
| --- | --- |
| `/` | Welcome, how it works, quickstart, troubleshooting, FAQ, support |
| `connect/` | Connecting Tradovate, Rithmic, TopstepX and NinjaTrader accounts |
| `settings/` | Follower copy settings, one page per section of the settings form |
| `dashboard/` | Overview, managing accounts, logs, journal, account settings |
| `guides/` | Task-based walkthroughs |
| `billing/` | Pricing, free trial and subscription management |

Navigation lives in `docs.json`. Writing rules are in `AGENTS.md`.

## Local preview

```bash
npm i -g mint
mint dev
```

Open `http://localhost:3000`. Check links with `mint broken-links`.

## Publishing

Changes pushed to `main` deploy automatically through the Mintlify GitHub app.
