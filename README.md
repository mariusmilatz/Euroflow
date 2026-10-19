# Euroflow Germany

An English-language financial life simulation grounded in the German system.

Euroflow keeps the useful learning loop of classic cash-flow board games - income, expenses, assets, liabilities, opportunities and market events - but replaces US-only assumptions with German financial realities.

## Play locally

Open `index.html` directly, or run a small local server:

```bash
python3 -m http.server 4173
```

Then visit [http://localhost:4173](http://localhost:4173). No build step, package manager or API keys are required.

## Included

- Three German career profiles
- Monthly income, expense, asset, debt and net-worth tracking
- ETF, property, career, household, tax, pension and market events
- German property-purchase friction and plausible consumer debt
- Emergency-fund and passive-income milestones
- Automatic browser-local saving
- Responsive desktop and mobile layouts
- Germany guide with links to official sources

## Important

This is an educational simulation, not tax, legal or investment advice. Values are rounded game assumptions. German laws, rates and personal circumstances vary and change over time.

## Project structure

- `index.html` - application shell
- `styles.css` - responsive visual system
- `app.js` - game state, events and calculations

## Hosting

Because the project is static, it can be hosted on GitHub Pages, Cloudflare Pages, Netlify, Vercel, or any ordinary web server.

## License and attribution

Euroflow is an original educational adaptation. It does not include the original CASHFLOW board, card text, artwork or branding. CASHFLOW is a trademark of its respective owner.
