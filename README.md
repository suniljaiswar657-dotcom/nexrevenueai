# NexRevenue AI

A mobile-friendly hybrid digital-business workspace MVP for India and global creators.

## Product vision

NexRevenue combines three potential revenue engines:
1. **SaaS subscriptions** — recurring plans for enhanced business tools.
2. **Digital products** — reusable templates, checklists and downloadable resources.
3. **Affiliate referrals** — transparent, trackable partner recommendations.

## Current MVP features

- Responsive landing page and workspace.
- Offer Studio that creates structured offer copy from user inputs (local template logic; no external AI API).
- Digital product shelf with locally added sample listings.
- Affiliate campaign tracker with outbound click counts.
- CSV export for saved affiliate campaigns.
- Manual revenue and sale recording dashboard.
- Browser-local persistence using localStorage.

## Run locally

No build step or package installation is required.

1. Clone this repository.
2. Open index.html in a modern browser.
3. Use the Offer Studio, add sample products/campaigns and record demo sales.

For local development, a simple static server is recommended:

    python -m http.server 8000

Then open http://localhost:8000.

## Important MVP limitations

This is a front-end validation MVP, **not yet a production SaaS**:
- No user accounts, cloud database or cross-device sync.
- No live AI model/API integration; Offer Studio uses deterministic templates.
- No payment checkout, subscription billing, tax calculation or refunds.
- Product cards are samples; digital file delivery is not implemented.
- Affiliate clicks are counted in this browser only; no partner-network conversion or payout integration.
- Dashboard figures are manually entered and are not verified financial records.

Do not accept payments or promise affiliate earnings until the relevant providers, security, legal disclosures, customer support and server-side verification are implemented.

## Next production milestones

1. Add secure authentication and a hosted database.
2. Add server-side AI generation with rate limits and usage controls.
3. Implement payment checkout, webhook verification and subscription entitlements.
4. Add secure digital downloads and order fulfilment.
5. Add server-side referral attribution and analytics.
6. Add privacy policy, terms, refund policy, data export/deletion and operational monitoring.

## Deployment

The project is a static website and can be deployed to Vercel, GitHub Pages or another static host. Configure the host to serve index.html from the repository root.

## License

MIT — see LICENSE.
