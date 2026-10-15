# Documentation project instructions

## About this project

- Customer-facing help center for CopyFlock (copyflock.com), a cloud futures trade copier.
- Built on [Mintlify](https://mintlify.com). Pages are MDX files with YAML frontmatter. Configuration and navigation live in `docs.json`.
- Every new page must be added to `navigation` in `docs.json`.

## Audience and tone

- Readers are futures traders, not developers. Write for someone who has never used a trade copier.
- Explain what to click and what happens, not how the system works internally. No architecture, servers, APIs, environment variables, or code.
- Use active voice and second person ("you"). One idea per sentence. Sentence case for headings.
- Bold UI labels exactly as they appear in the dashboard: click **Add account**.

## Content boundaries

- These docs are about CopyFlock only. Never mention other products, brands or the infrastructure behind CopyFlock.
- Only document what the dashboard actually does. Check the UI labels and behavior in the `copyflock.com-frontend` repo before writing, and don't copy marketing claims without verifying them.
- Don't promise prop firm compliance. CopyFlock doesn't read or enforce firm rules.
- Prices, trial terms and limits must match the site (`src/config/site.ts` in the frontend): Starter $29/month or $290/year for up to 10 accounts, Pro $49/$490 for up to 20, Unlimited $99/$990 (fair use up to 200). The lead counts as an account. 7-day free trial on 2 accounts with a card; followers copy a fixed 1 contract during the trial.

## Terminology

- **CopyFlock** (capital F), never "Copyflock".
- **Lead** and **follower** (not master and slave).
- **Contracts**, not lots.
- **Sizing method**, **symbol mapping**, **symbol filter**, **account protection**: use the dashboard's names for settings.
- **Seats**: the number of accounts on a plan.
