# Azure Dragon Trading Bot — Landing Page

Landing page for the Azure Dragon automated XAUUSD (gold) trading bot, ₱1,500/month subscription.

Single self-contained `index.html`: no build step, no dependencies. The 3D wireframe dragon is drawn live on a `<canvas>` with plain JavaScript. Fonts load from Google Fonts.

## Preview locally
Open `index.html` in any browser.

## Publish with GitHub Pages
1. Repo **Settings → Pages**
2. **Source:** Deploy from a branch → `main` / `(root)` → Save
3. Live in about a minute at `https://<username>.github.io/<repo-name>/`

## Before going live — replace placeholders
Search `index.html` for `[`:
- `[PAYMENT LINK]` — subscribe button
- `[X]%` daily loss limit, `[Y]%` equity stop
- `[PLATFORM, e.g. MetaTrader 5]`
- `[support channel]`, `[CONTACT EMAIL]`

Every rule described on the page (stop loss, daily loss limit, equity stop) must match what the bot actually does.

## Risk notice
Trading leveraged products such as gold CFDs carries a high risk of loss. This page and the bot are not financial advice.
