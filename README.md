# Blues (blues-wireless)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Blues (formerly Blues Wireless) is an IoT connectivity platform that provides Notecard hardware modules and the Notehub cloud service for routing device data from edge devices to cloud applications. The Notehub REST API enables developers to manage fleets of cellular, satellite, LoRa, and Wi-Fi connected devices across 130+ countries. Blues follows a consumption-based pricing model with no subscription fees, charging per ingressed event beyond a 5,000-event free monthly allowance bundled with each Notecard hardware purchase.

APIs.json: [https://raw.githubusercontent.com/api-evangelist/blues-wireless/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/blues-wireless/refs/heads/main/apis.yml)

Naftiko: [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=blues-wireless-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=blues-wireless-api-evangelist&utm_content=repo)

## Tags

IoT, Cellular, Connectivity, Device Management, Fleet Management, Satellite, LoRa, WiFi, Notecard, Notehub

## APIs

### Notehub API
The Notehub REST API provides programmatic access to Blues Notehub for managing IoT device fleets, routing events, configuring projects, monitoring device health, and handling billing. It covers authorization, billing accounts, devices, events, jobs, monitoring, organizations, projects, routes, and usage reporting.

- Documentation: https://dev.blues.io/api-reference/notehub-api/api-introduction/
- OpenAPI: https://raw.githubusercontent.com/blues/notehub-js/main/openapi.yaml
- Base URL: https://api.notefile.net

### Notecard API
The Notecard API is the firmware-level JSON API for interacting with Blues Notecard hardware modules directly over serial or I2C. It supports card, dfu, env, file, hub, note, ntn, var, and web request categories.

- Documentation: https://dev.blues.io/api-reference/notecard-api/introduction/

## Plans, Rate Limits, and FinOps

### Plans
Blues offers an Essentials (freemium) plan and an Enterprise plan.

- **Essentials**: 5,000 free events/month; $0.000750 per additional event; 7 API req/min (10,200/day) free
- **Enterprise**: Starting at $1,000/month; 50%+ discount off Essentials rate; custom API rate limits; 4-hour support SLA

Full details: [plans/blues-wireless-plans-pricing.yml](plans/blues-wireless-plans-pricing.yml)

### Rate Limits
- Essentials: 7 API requests per minute, 10,200 per day per billing account
- Enterprise: Custom higher limits
- Throttle response code: 429
- Authentication: Personal Access Tokens (recommended), OAuth 2.0 Client Credentials, or legacy session tokens

Full details: [rate-limits/blues-wireless-rate-limits.yml](rate-limits/blues-wireless-rate-limits.yml)

### FinOps
Billing model is consumption-based with no subscription fees. Key meters: events ingressed ($0.000750/event after free allowance), connectivity assurance data top-ups ($10 NA / $15 international per 500MB), and API requests (free up to daily limit).

Full details: [finops/blues-wireless-finops.yml](finops/blues-wireless-finops.yml)

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://blues.com |
| Developer Portal | https://dev.blues.io |
| Documentation | https://dev.blues.io/api-reference/ |
| GitHub Organization | https://github.com/blues |
| Blog | https://dev.blues.io/blog/ |
| Changelog | https://dev.blues.io/blog/whats-new-in-notehub/ |
| Pricing | https://blues.com/pricing/ |
| Status Page | https://status.notehub.io |
| LinkedIn | https://www.linkedin.com/company/buildwithblues |
| X | https://twitter.com/buildwithblues |
| SDKs | https://blues.github.io/opensource/ |

## Maintainers

- Kin Lane / kin@apievangelist.com
