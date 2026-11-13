# Awesome-Customer-Support-Client-Portal

## Top Customer Support & Client Portal Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Self-Service Help Centers, Ticket Submission & Branded Client Workspaces*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Customer Support & Client Portals**. These tools give customers a branded destination to help themselves—searching knowledge bases, submitting and tracking tickets, and accessing account resources—reducing inbound support volume while improving resolution speed.

**Examples** include Zendesk Help Center, Freshdesk, HubSpot Service Hub, Salesforce Experience Cloud, Zoho Desk, Help Scout, Clinked, SuiteDash, and open-source alternatives like Znuny, Zammad, and Faveo Helpdesk (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted support portals, open-source help centers, and community-driven client workspaces—ideal for organizations seeking data sovereignty and eliminating per-agent licensing costs. The open-source landscape splits cleanly: Znuny and Zammad deliver full support portals with self-service interfaces, while ClientShare and Atrium focus on branded file-exchange portals for agencies [citation:2][citation:5][citation:12].

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Zendesk Help Center](https://www.zendesk.com/)** | Support-first portal pairing ticketing with a knowledge base, community forums, and AI-assisted service features (AI agents, intelligent triage, Auto Assist) depending on plan. Best for established multi-channel support teams. File sharing and project work usually live elsewhere [citation:1][citation:8]. | Quote-only (bundled with Zendesk Suite) | No free tier; trial via sales |
| **[Freshdesk](https://www.freshworks.com/freshdesk/)** | Self-service portal up quickly with help center, ticket automations, and SLA tracking. Best for small teams on a budget—advanced features sit on higher tiers [citation:1]. | Growth: ~$19/agent/month (annual); Pro: ~$55; Enterprise: ~$89 | No permanent free tier; trial available |
| **[HubSpot Service Hub](https://www.hubspot.com/products/service)** | Customer portal (formerly customer portal) lets customers log in to view and reply to their own tickets, with Smart CRM context alongside each request. Most valuable if sales, marketing, and service already run on HubSpot; conversations not tied to a ticket won't appear [citation:1][citation:8]. | Quote-only (Professional/Enterprise required for portal) | No free tier for portal; trial via sales |
| **[Salesforce Experience Cloud](https://www.salesforce.com/products/experience-cloud/)** | Builds customer or partner portals on top of Salesforce data. Customers browse knowledge articles, open and track cases, and authenticate via Salesforce or SSO. Requires Salesforce admin expertise to set up [citation:1][citation:8]. | Quote-only (enterprise) | No free tier; demo via sales |
| **[Zoho Desk](https://www.zoho.com/desk/)** | Help center with ticketing, workflows, and SLA tracking. Work modes can sort tickets by customer status in Zoho CRM—best fit when other tools are Zoho [citation:1]. | Standard: $14/agent/month (annual); Express: $7 | Free: up to 3 agents; 15-day trial |
| **[Help Scout](https://www.helpscout.com/)** | Combines shared inbox, knowledge base, and help widget. Short learning curve; outgrown if complex workflows or deep portal customization are needed [citation:1]. | Standard: $25/user/month (annual); Plus: $50 | Free: 5 users, 1 Inbox, 1 Docs site |
| **[Clinked](https://www.clinked.com/)** | Document-centric white-label client portal for agencies and professional services. Custom domains and email domains carry your brand; files, discussions, and approvals in one place. Not built for high-volume ticketing—pair with a help desk if support dominates [citation:1]. | Standard: ~$239/month (100 members) | Free trial available |
| **[SuiteDash](https://suitedash.com/)** | All-in-one bundle of CRM, invoicing, projects, and client portal in one subscription. Many features can slow setup as you decide what to enable [citation:1]. | Start: $19/month (unlimited users) | 14-day free trial |
| **[Softr](https://www.softr.io/)** | Builds portals on top of Airtable or spreadsheet data with prebuilt blocks and AI Co-Builder. Plans cap the number of app users, so large customer bases push to higher tiers [citation:1][citation:8]. | Free tier available; paid from ~$24/month | Free plan with limited users |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Znuny](https://github.com/znuny/Znuny)** | [![Stars](https://img.shields.io/github/stars/znuny/Znuny?style=social&color=white)](https://github.com/znuny/Znuny/stargazers) | **Full open-source helpdesk with customer self-service interface.** Fork of OTRS with 10+ years of community development, 30K+ GitHub commits, and 200K+ forum posts [citation:2]. Customer portal lets users submit tickets via preset forms, browse FAQ/knowledge base, and communicate efficiently. Supports SLAs, templates/snippets, and third-party system integration (CRM, catalogues, databases). On-premise or cloud; free forever under open-source licensing [citation:2]. |
| **[Zammad](https://github.com/zammad/zammad)** | [![Stars](https://img.shields.io/github/stars/zammad/zammad?style=social&color=white)](https://github.com/zammad/zammad/stargazers) | Web-based open-source helpdesk and customer support platform (AGPLv3) covering email, chat, telephone, and social media [citation:7][citation:14]. Includes knowledge base and customer-facing portal for ticket submission and tracking. Owned by the independent Zammad Foundation. A mature Zendesk alternative for teams wanting full data control. |
| **[Faveo Helpdesk](https://github.com/ladybirdweb/faveo-helpdesk)** | [![Stars](https://img.shields.io/github/stars/ladybirdweb/faveo-helpdesk?style=social&color=white)](https://github.com/ladybirdweb/faveo-helpdesk/stargazers) | Self-hosted open-source support ticketing and helpdesk system (OSL-3.0). Turns inbound email and web requests into tickets, routes to departments, enforces SLA plans, and provides a **customer self-service portal** plus knowledge base [citation:11]. Laravel 9/PHP 8.2 stack with MariaDB. No per-seat or per-agent fee. Available as pre-configured Ubuntu 24.04 image via Microsoft Marketplace [citation:11]. |
| **[ClientShare](https://github.com/pixelcop/clientshare)** | [![Stars](https://img.shields.io/github/stars/pixelcop/clientshare?style=social&color=white)](https://github.com/pixelcop/clientshare/stargazers) | **Secure, branded client portal for file exchange and document collection.** Keeps sensitive files out of email threads. Features branded portal settings (site title, logo, primary color), expiring secure links, user/role-based access control, client/folder/file organization, and email-driven invite/password workflows [citation:5]. Go + Vue single deployable service. SQLite/local storage by default, upgrades to Postgres/MySQL/S3. Docker Compose quick start [citation:5]. |
| **[Atrium](https://hub.docker.com/r/vibralabs/atrium)** | — | Self-hosted client portal for agencies and freelancers. Replaces shared drives and scattered emails with a branded login portal you host yourself [citation:12]. Features project management with custom status pipelines, file sharing via S3/MinIO/Cloudflare R2/local, white-label branding (colors, logo), role-based access (owner/admin for team, member for clients), and email notifications via Resend. Built-in PostgreSQL—no separate database container needed. Single Docker command to start [citation:12]. |
| **[Apache Answer](https://github.com/apache/incubator-answer)** | [![Stars](https://img.shields.io/github/stars/apache/incubator-answer?style=social&color=white)](https://github.com/apache/incubator-answer/stargazers) | Q&A platform software for teams at any scale—community forum, help center, or knowledge management platform. ~16k stars [citation:3]. Useful as a self-hosted knowledge base component of a support portal, though it is not a full ticketing system with customer account management. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Helpy](https://github.com/helpyio/helpy)** | [![Stars](https://img.shields.io/github/stars/helpyio/helpy?style=social&color=white)](https://github.com/helpyio/helpy/stargazers) | Modern open-source helpdesk customer support application (MIT). Features knowledgebase, community discussions, and support tickets integrated with email [citation:9]. A lighter-weight option for teams wanting a support portal without enterprise complexity. |
| **[Frappe Wiki](https://github.com/frappe/wiki)** | [![Stars](https://img.shields.io/github/stars/frappe/wiki?style=social&color=white)](https://github.com/frappe/wiki/stargazers) | Open-source documentation tool for product guides, help centers, and company handbooks [citation:10]. Rich text editor, change requests with review workflow, fast reader with search, PDF download, and analytics. GitHub Sync keeps spaces aligned with Markdown files. Best used as the **knowledge base layer** alongside a ticketing system. |

**Frameworks for building custom systems**: Combine **Znuny** or **Zammad** for full helpdesk portals with customer self-service, **ClientShare** or **Atrium** for branded file-exchange portals, and **Frappe Wiki** or **Apache Answer** for the knowledge base layer—all deployable via Docker without per-agent SaaS fees. Choose based on whether your portal's primary job is ticket resolution (Znuny, Zammad, Faveo) or document exchange (ClientShare, Atrium) [citation:2][citation:5][citation:11].

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Support portals handle customer PII and support conversations; enforce role-based access, audit logging, and compliance with applicable data protection regulations.
- **Open-source support portals split into two distinct categories.** Znuny and Zammad provide full ticketing with customer self-service interfaces [citation:2][citation:7]. ClientShare and Atrium focus on branded document exchange for agencies—they are not ticketing systems [citation:5][citation:12]. Match the tool to your portal's primary job. SaaS portal features vary by plan tier: HubSpot's customer portal requires Professional or Enterprise [citation:1], and Freshdesk gates advanced portal features behind higher plans [citation:1]. Always verify current feature availability and pricing against vendor pages before committing.

---

**Made for support operations managers, helpdesk administrators, agency owners, and developers building customer-facing support infrastructure.**  
Let's make customer support portals more open, branded, and self-service.
