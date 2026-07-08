# Gram Pacific Inc. — Website + Talent OS Platform

Single-file web application for Gram Pacific Inc., a managed remote staffing company connecting US, Canadian, and Australian SMEs with dedicated full-time professionals.

## What's inside

- **Public website**: Home, Services, Pricing (with interactive discount calculator), About Us, Careers, Contact
- **SEO role landing pages**: bookkeeper, accountant, executive assistant, customer service, digital marketer, software developer
- **Talent OS platform** (behind Log in): Admin Control, SME Client Portal, and Talent Portal demos

## Running it

Everything is in `index.html`. No build step, no dependencies. Open the file in a browser or serve it from any static host (GitHub Pages, Netlify, Cloudflare Pages).

## Deploying to GitHub Pages

1. Push this folder to a GitHub repository
2. Repository Settings → Pages → Source: `main` branch, root folder
3. Site goes live at `https://<username>.github.io/<repo-name>/`

## Notes

- Navigation uses hash routing (`#/pricing`, `#/role/bookkeeper`), so it works on any static host with no server configuration.
- For production SEO, role pages should eventually be server-rendered at real URLs. All content is already structured for that migration.
- Demo login requires no credentials; production would use email + password with SSO and 2FA.

© 2026 Gram Pacific Inc.
