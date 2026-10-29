# Blues

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

Blues (formerly Blues Wireless) is an IoT connectivity platform that provides hardware modules called Notecards and a cloud service called Notehub for routing device data from edge devices to cloud applications. The Notehub REST API enables developers to manage fleets of cellular, satellite, LoRa, and Wi-Fi connected devices across 130+ countries. Developers can use the API to retrieve device events, manage projects and fleets, configure routes to downstream cloud services, and monitor device health. Blues follows a consumption-based pricing model with no subscription fees, charging per ingressed event beyond a free monthly allowance bundled with each Notecard hardware purchase.

**Areas:** IoT · Cellular · Connectivity · Device Management · Fleet Management · Satellite · LoRA · Wi-Fi · Notecard · Notehub

## Blues on APIs.io

Everything profiled for Blues is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/blues-wireless/](https://apis.io/providers/blues-wireless/)** — or go straight to one of the APIs or properties below.

### APIs (14)

- [Notecard API](https://apis.io/apis/blues-wireless/blues-wireless-notecard-api/) — The Notecard API is the firmware-level JSON API for interacting with Blues Notecard hardware modules directly over serial or I2C. It supports card, dfu,…
- [Blues Alert API](https://apis.io/apis/blues-wireless/blues-wireless-alert-api/) — The alert API from Blues — 1 operation(s) for alert.
- [Blues Authorization API](https://apis.io/apis/blues-wireless/blues-wireless-authorization-api/) — Authorization operations
- [Blues Billing Account API](https://apis.io/apis/blues-wireless/blues-wireless-billing-account-api/) — Billing Account operations
- [Blues Device API](https://apis.io/apis/blues-wireless/blues-wireless-device-api/) — Device operations
- [Blues Event API](https://apis.io/apis/blues-wireless/blues-wireless-event-api/) — Event retrieval operations
- [Blues external devices API](https://apis.io/apis/blues-wireless/blues-wireless-external-devices-api/) — APIs for events and sessions for external devices
- [Blues Jobs API](https://apis.io/apis/blues-wireless/blues-wireless-jobs-api/) — Batch job operations
- [Blues Monitor API](https://apis.io/apis/blues-wireless/blues-wireless-monitor-api/) — The monitor API from Blues — 2 operation(s) for monitor.
- [Blues Organization API](https://apis.io/apis/blues-wireless/blues-wireless-organization-api/) — Organization operations
- [Blues Project API](https://apis.io/apis/blues-wireless/blues-wireless-project-api/) — Project operations
- [Blues Route API](https://apis.io/apis/blues-wireless/blues-wireless-route-api/) — Route operations
- [Blues Usage API](https://apis.io/apis/blues-wireless/blues-wireless-usage-api/) — Project Usage information related to events, route logs, sessions, and data usage
- [Blues Webhook API](https://apis.io/apis/blues-wireless/blues-wireless-webhook-api/) — Webhook APIs for non-notecard event ingestion

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Blues Wireless Agentic Access](https://apis.io/agentic-access/blues-wireless/blues-wireless-agentic-access/)

#### JSON Schema (11)

The data models the API reads and writes.

- [BillingAccount](https://apis.io/schemas/blues-wireless/blues-wireless-billing-account/)
- [Device](https://apis.io/schemas/blues-wireless/blues-wireless-device/)
- [Event](https://apis.io/schemas/blues-wireless/blues-wireless-event/)
- [Firmware](https://apis.io/schemas/blues-wireless/blues-wireless-firmware/)
- [Fleet](https://apis.io/schemas/blues-wireless/blues-wireless-fleet/)
- [Job](https://apis.io/schemas/blues-wireless/blues-wireless-job/)
- [Monitor](https://apis.io/schemas/blues-wireless/blues-wireless-monitor/)
- [Note](https://apis.io/schemas/blues-wireless/blues-wireless-note/)
- [Notefile](https://apis.io/schemas/blues-wireless/blues-wireless-notefile/)
- [Project](https://apis.io/schemas/blues-wireless/blues-wireless-project/)
- [HttpRoute](https://apis.io/schemas/blues-wireless/blues-wireless-route/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Blues Wireless Context](https://apis.io/jsonld/blues-wireless/blues-wireless-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Blues Wireless Vocabulary](https://apis.io/vocabularies/blues-wireless/blues-wireless-vocabulary/)

#### Examples (1)

Example requests and responses.

- [Blues Wireless Notehub Api Examples](https://apis.io/examples/blues-wireless/blues-wireless-notehub-api-examples/)

#### Collections (26)

Postman and Open Collection request collections.

- [Notehub alert API](https://apis.io/collections/blues-wireless/open-blues-wireless-alert-api/)
- [Notehub alert authorization API](https://apis.io/collections/blues-wireless/open-blues-wireless-authorization-api/)
- [Notehub alert billing_account API](https://apis.io/collections/blues-wireless/open-blues-wireless-billing-account-api/)
- [Notehub alert device API](https://apis.io/collections/blues-wireless/open-blues-wireless-device-api/)
- [Notehub alert event API](https://apis.io/collections/blues-wireless/open-blues-wireless-event-api/)
- [Notehub alert external devices API](https://apis.io/collections/blues-wireless/open-blues-wireless-external-devices-api/)
- [Notehub alert jobs API](https://apis.io/collections/blues-wireless/open-blues-wireless-jobs-api/)
- [Notehub alert monitor API](https://apis.io/collections/blues-wireless/open-blues-wireless-monitor-api/)
- [Notehub alert organization API](https://apis.io/collections/blues-wireless/open-blues-wireless-organization-api/)
- [Notehub alert project API](https://apis.io/collections/blues-wireless/open-blues-wireless-project-api/)
- [Notehub alert route API](https://apis.io/collections/blues-wireless/open-blues-wireless-route-api/)
- [Notehub alert usage API](https://apis.io/collections/blues-wireless/open-blues-wireless-usage-api/)
- [Notehub alert webhook API](https://apis.io/collections/blues-wireless/open-blues-wireless-webhook-api/)
- [Notehub alert API](https://apis.io/collections/blues-wireless/postman-blues-wireless-alert-api/)
- [Notehub alert authorization API](https://apis.io/collections/blues-wireless/postman-blues-wireless-authorization-api/)
- [Notehub alert billing_account API](https://apis.io/collections/blues-wireless/postman-blues-wireless-billing-account-api/)
- [Notehub alert device API](https://apis.io/collections/blues-wireless/postman-blues-wireless-device-api/)
- [Notehub alert event API](https://apis.io/collections/blues-wireless/postman-blues-wireless-event-api/)
- [Notehub alert external devices API](https://apis.io/collections/blues-wireless/postman-blues-wireless-external-devices-api/)
- [Notehub alert jobs API](https://apis.io/collections/blues-wireless/postman-blues-wireless-jobs-api/)
- [Notehub alert monitor API](https://apis.io/collections/blues-wireless/postman-blues-wireless-monitor-api/)
- [Notehub alert organization API](https://apis.io/collections/blues-wireless/postman-blues-wireless-organization-api/)
- [Notehub alert project API](https://apis.io/collections/blues-wireless/postman-blues-wireless-project-api/)
- [Notehub alert route API](https://apis.io/collections/blues-wireless/postman-blues-wireless-route-api/)
- [Notehub alert usage API](https://apis.io/collections/blues-wireless/postman-blues-wireless-usage-api/)
- …and 1 more published on APIs.io

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Blues — jsonschema rules](https://apis.io/rules/blues-wireless/blues-wireless-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Blues Wireless Authentication](https://apis.io/security/blues-wireless/blues-wireless-authentication/)
- [Blues Wireless Domain Security](https://apis.io/security/blues-wireless/blues-wireless-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Blues Wireless Plans Pricing](https://apis.io/plans/blues-wireless/blues-wireless-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Blues Wireless Rate Limits](https://apis.io/rate-limits/blues-wireless/blues-wireless-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Blues Wireless Finops](https://apis.io/finops/blues-wireless/blues-wireless-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://blues.com)
- [Documentation](https://dev.blues.io/api-reference/)
- [Pricing](https://blues.com/pricing/)
- [Changelog](https://dev.blues.io/blog/whats-new-in-notehub/)
- [Blog](https://dev.blues.io/blog/)
- [GitHub](https://github.com/blues)
- [Status](https://status.notehub.io)

## API Evangelist rating

**Kin Score 43.1** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 61.4 |
| Contract governance | 23.5 |
| Operational transparency | 42.1 |
| Developer ergonomics | 45.2 |
| Access clarity | 15.8 |

**Agent readiness 32.9** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | yes |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/blues-wireless/](https://apis.io/providers/blues-wireless/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Blues: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/blues-wireless/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
