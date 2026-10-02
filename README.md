# HomeFinder — Prime European Real Estate Marketplace

> Built by **Nkechi Anna Ahanonye** — Cloud & DevOps Engineer
> *I turn 3 AM-breaking deployments into 1-min pipelines with AWS + Ansible + Terraform | Building security-first AI agents on Amazon Bedrock AgentCore | AI Governance on AWS certified*

Live demo: https://nkydigitech.github.io/homefinder-webapp/

A modern, production-style real estate marketplace for buyers, investors, property owners, and certified brokers across Central Europe's historic capitals — **Budapest, Vienna, Amsterdam, Prague, and Warsaw**.

## Key Features

1. **Home Page** — hero with multi-parameter search (buy/rent, city, architecture type, max budget, bedrooms), featured residences, capital explorer, and value propositions (legal title audits, certified brokers, concierge viewings).
2. **Property Search** — advanced filtering sidebar (transaction type, city, price, bed/bath, area, parking, furnishing), live text search across titles, districts, and streets, plus a simulated map visualizer.
3. **Property Details** — image gallery with lightbox, spec bar (bedrooms, bathrooms, area, energy rating), amenities grid, multi-level floor plan viewer, neighborhood map, certified broker card, inquiry form, and a schedule-viewing modal with real-time slot selection.
4. **Favorites & Comparison** — saved shortlist with local persistence and a side-by-side comparison matrix for up to 4 properties.
5. **Agent Directory** — certified broker profiles with credentials, spoken languages, active listings, and direct messaging.
6. **List Your Property** — 5-step guided wizard with live preview before publishing.
7. **User Dashboard** — shortlist, viewed history, inquiries log, viewings tracker, and notification preferences.
8. **Admin Console** — platform stats, property inventory with featured toggles, legal/compliance verification queue, inquiry dispatch, broker and user management.

## Tech Stack

React 19 · TypeScript · Vite · Tailwind CSS v4 · Lucide React · Local storage persistence (no external backend required) · Docker · Terraform (Azure) for infrastructure

## Run It Locally

```bash
npm install
npm run dev        # development server on port 3000
npm run build      # production build
```

### Docker

```bash
docker compose up --build
```

## Infrastructure (Terraform on Azure)

The `terraform-module/` directory contains a modular Azure infrastructure setup:

- `modules/network` — resource group, virtual network, subnet, NSG, and network interface
- `modules/compute` — virtual machine provisioning

```bash
cd terraform-module
terraform init
terraform plan
terraform apply
```

## Connect

- Portfolio: https://nkydigitech.github.io/nky-portfolio/
- GitHub: https://github.com/nkydigitech
- LinkedIn: https://www.linkedin.com/in/nkechiahanonye
