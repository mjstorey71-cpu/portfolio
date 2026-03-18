# Michael Storey — Portfolio Case Studies

Static portfolio site hosted via GitHub Pages at [portfolio.michael-storey.com](https://portfolio.michael-storey.com).

## Structure

```
index.html              — Case study index (17 cards)
_card-images/           — Card thumbnail images (800x400px)
rentedge/               — RentEdge: Embedding RentSpree into the MLS Ecosystem
messaging/              — Messaging: Transforming Tenant-Landlord Communication
landlord-fintech/       — Landlord FinTech: Financial Services for Property Owners
design-system/          — Design System: PXD System Architecture
ai-power-up/            — AI Power Up: Agentic AI at RentSpree
app-redesign/           — App Redesign: RentSpree Mobile and Web Overhaul
transforming-rentspree/ — Transforming RentSpree: From Feature Factory to Product-Led
inside-amazon/          — Inside Amazon: Global Employee Services UX
amazon-imaging/         — Amazon Imaging as a Service
amazon-prime/           — Amazon Prime: UX Strategy
amazon-creative-services/ — Amazon Creative Services: Global Scale
amazon-gift-guides/     — Amazon Consumer Gift Guides
amazon-banner/          — Amazon Banner Tool
hackathon/              — Hackathon
ai-uxr/                 — AI-Powered UX Research
voc/                    — Voice of Customer
pqs/                    — Product Quality Scoring
CNAME                   — Custom domain config for GitHub Pages
```

## Hosting

Served via GitHub Pages. The `CNAME` file maps the custom subdomain `portfolio.michael-storey.com` to this repo. DNS is configured as a CNAME record at the domain registrar pointing `portfolio` to `[github-username].github.io`.

## Updating Content

All case study files are self-contained HTML. To update a case study, edit the relevant HTML file in its folder and push to the `main` branch. Changes go live within a few minutes.

To replace card thumbnail images, drop new files into `_card-images/` using the existing filenames (01-rentedge.jpg through 17-pqs.jpg) and push.
