# Gram Pacific Inc. — Website + Talent OS Platform

Single-file web application for Gram Pacific Inc., a managed remote staffing company connecting US, Canadian, and Australian SMEs with dedicated full-time professionals.

## What's inside

- **Public website**: Home (with high-paying flagship roles showcase), Services (91-role directory across 11 categories), Pricing (two tiers with interactive discount calculator), Blog (6 full articles), About Us, Careers, Contact
- **91 SEO role landing pages**: every role from executive assistant to machine learning engineer has its own page with scope, tools, pricing, and FAQs
- **Two-tier pricing**: standard roles $3,000/mo flat; technical roles $4,000/mo flat
- **Talent OS platform** (behind Log in): Admin Control, SME Client Portal, and Talent Portal demos
- **SEO/AIO layer**: 1,000+ keyword terms, JSON-LD structured data (Organization, Service, FAQ, ItemList, Blog), sitemap, robots.txt, and llms.txt for AI-engine discoverability

## Running it

Everything is in `index.html`. No build step, no dependencies. Open the file in a browser or serve it from any static host (GitHub Pages, Netlify, Cloudflare Pages).

## Deploying to GitHub Pages

1. Push this folder to a GitHub repository
2. Repository Settings → Pages → Source: `main` branch, root folder
3. Site goes live at `https://<username>.github.io/<repo-name>/`
4. Replace YOUR-USERNAME in robots.txt and sitemap.xml with your GitHub username

## Notes

- Navigation uses hash routing (`#/pricing`, `#/role/grant-writer`, `#/post/true-cost-of-hiring-2026`), so it works on any static host with no server configuration.
- For production SEO, role and blog pages should eventually be server-rendered at real URLs. All content is data-driven and already structured for that migration.
- Demo login requires no credentials; production would use email + password with SSO and 2FA.

© 2026 Gram Pacific Inc.
